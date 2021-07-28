# Glossary 

List of terminology used in the conductor.

## Services

Source code for following executables can be found in this repository

### Solution Design Service

- Handles events from from config loader and persists solutions.
- Allows a soiution run to be triggered

### Solution Host Service

- Handles the running of a solution

### Component Host Service

- Handles the running of a component
- Integrates with legacy EDM to run components

### Conductor CLI

- Allows solutions to be triggered from the command line

## Ubiquitous Language

### Component
- Excutable unit of work in a solution,
- Can be batched or streamed 

### Connection
- Link between two components
- Can be of type Success, Failure or OnCompletion

### Input / Output

- Connections join a component output to another component input

### Solutions 

- Contains 1 or more components, and 0 or more solutions linked by connections
- Is called "nested" if referenced by another Solution 
- Can be "[exploded](Exploding.md)" to remove nesting and create 1 large solution

### Orchestrated Start/End

- Contained within a legacy solution which has been "[exploded](Exploding.md)" to remove nesting and create 1 large solution
- Is contained within the exploded solution graph as a component
- Corresponds to a call to the legacy Process Launcher API to start and end a Legacy Solution

## Events

The conductor is event sourced. This means the current state of domain objects is determined by a left-fold over a sequence of historical events in a stream.

This sections outlines the events that can be found within the various streams in the conductor.

To view the contents of an event search the codebase for the type name corresponding to the header.

### Solution Design Service

The events in this section can be found in the collection `solution-events`

#### Solution Stream Events

The solution domain object in the design host represents an uploaded solution from legacy EDM. Eventually this service will facilitate the modification of solutions or their design from scratch.

##### SolutionCreatedEvent

The solution has been created with a specified name and tenant 

##### SolutionUploadedEvent

The solution is apart of an [upload](ADR/0001-persisting-solutions-from-configloader.md) with a specified upload ID.

##### SolutionUploadCompletedEvent

Indicates the solution is a part of a completed uploaded of 1 or more solutions.

##### AddComponentEvent

Component has been added to solution.

##### LegacyComponentSettingsInitialised

If a component added to the solution by [AddComponentEvent](#addcomponentevent) represents a component in Legacy EDM, this event specifies the settings to allow this component to be called by the conductor

##### ConnectComponentsEvent

Two components have been linked together via specified inputs and outputs. (see AddInputEvent and AddOutputEvent)

##### PartitionComponentsEvent

##### AddInputEvent

An input has been added to a component

##### AddOutputEvent

An output has been added to a component

#### Solution Upload Saga Stream Events

These events can be found in the saga store collection `solutionuploadsagastate-events`

##### SolutionUploadedSagaEvent

One of potentially many solutions in an upload has been completed

##### SolutionUploadCompletedSagaEvent

The upload of *all* solutions has been completed
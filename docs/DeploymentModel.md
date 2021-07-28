# Deployment Model

The Conductor will run on EDM kubernetes clusters. The first target environment is an EKS cluster running on AWS.

The following gitlab repositories are used to create automated deployments to this target environment.

|Repository  | Comment  |
|--|--|
| [Conductor IAC](https://git.mdevlab.com/medm/team-conductor/conductor-iac) | A repository of Terraform modules for the required infrastructure to maintain an EDM environment, including the Conductor, running on EKS. The Terraform modules are based on those maintained in the [OCTO terraform modules repository](https://git.mdevlab.com/octo/terraform-modules/) where possible.|
| [Conductor Flux](https://git.mdevlab.com/medm/team-conductor/conductor-flux) |  A [flux](https://docs.fluxcd.io/en/1.22.0/) repository that maintains the desired deployment state of the services that make up the EDM environments built using the infrastructure as code described above.|


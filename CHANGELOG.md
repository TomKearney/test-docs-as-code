# CHANGE LOG

> All notable changes to this project will be documented in this file. See
> [Conventional Commits](https://www.conventionalcommits.org) for commit guidelines.

## v0.23.0 [2021-07-23]

### Features

* edmc-6307: allow components within solutions with InAdvance locks to run [fd55db81](fd55db81390f13a1fc5f192825869376cb3874ab)


## v0.22.3 [2021-07-22]

### Patches

* EDMC-6430:  Recognise failure path routes when evaluating next steps in solution [a1c3787a](a1c3787ad8ff606646028b0f381e9a2b001175da)


## v0.22.1 [2021-07-19]

### Patches

* EDMC-6361:  Creates E2E test to validate skipping of series processes that succeed a failed process [a55aa02b](a55aa02b3443c9b7986fbfab986d4c32a0890961)

## v0.22.0 [2021-07-15]

### Features

* EDMC-6361: Implement orchestration of components in series [8294d523](8294d5234c919ddf7363e86b35985f7d8e60988f)

## v0.21.3 [2021-07-08]

### Patches

* edmc-6302: add a more complex run solution test and supporting [e7e5f751](e7e5f751fc5725cf61d3b9ce416199e2b0290300)

## v0.21.2 [2021-07-08]

### Bug Fixes

* sonarqube security fix [25f33697](25f33697ef9a3d0641fe684407b34dc1414d5bd2)

## v0.21.1 [2021-07-07]

### Patches

* edmc-6302: add e2e test which runs solution [4b67a629](4b67a6298a99c4f43d4c25231aa37498aa5bff2b)

## v0.21.0 [2021-07-07]

### Features

* EDMC-6301: Consolidate outcomes from components to solution status on completion [573f5679](573f5679a6c6c734efa4178a15978ac67820900f)

## v0.20.3 [2021-07-06]

### Patches

* edmc-6302: reduce duplicate lines highlighted by sonar [cf572041](cf572041e18926f1754240e9ada5f858519b126f)

## v0.20.2 [2021-07-06]

### Patches

* edmc-6302: introduce end-to-end tests [c7feee5d](c7feee5dd3a38dd4f2aff4924f7635779cfeb983)

## v0.20.1 [2021-07-06]

### Bug Fixes

* edmc-6304: add support for wait, result, and log component types and remove redundant code [ec9e0801](ec9e0801be9b51ef1563037b2eaf320417668d2d)

## v0.20.0 [2021-06-30]

### Features

* edmc-6092: running solutions [c344dd8f](c344dd8f125cc592fd365f736621f89ddaeb1cb0)

## v0.19.1 [2021-06-23]

### Bug Fixes

* edmc-6225: add missing component types [e23ca9f9](e23ca9f9173e23739f7296d78c1f34303bbbfc74)

## v0.19.0 [2021-06-17]

### Features

* edmc-5968: explode solution on a request to run [fc133f3c](fc133f3c13a0dc6897f09209f16f574ffa71baeb)

## v0.18.0 [2021-06-10]

### Features

* allow solution to be uploaded more than once [977e540f](977e540fd117fd08d1b6cb6018302556fa96b8d2)

## v0.17.2 [2021-06-10]

### Patches

* add config loader test double with docs [dd139b6f](dd139b6f041c2c17182f607f28435bab6607cdd8)

## v0.17.1 [2021-06-10]

### Bug Fixes

* EDMC-6094: relocate saga store to tenanted database and related changes [7cbe45c4](7cbe45c476389fa5ee33fb111434eca487653691)

## v0.17.0 [2021-06-02]

### Features

* publish docker images for solution and component host, and update [a6a78beb](a6a78bebb211fa498975f7858456ebc6965d55a0)

## v0.16.4 [2021-05-28]

### Patches

* edmc-5192: ADR for solution persistence [3d562fbf](3d562fbf9e8379f5a8463a1fc407ec1d688ea9ac)

## v0.16.3 [2021-05-27]

### Bug Fixes

* retry connection if pulsar cannot be reached [07b92664](07b9266456ba5e048cef75352f19390caaab6f94)

## v0.16.2 [2021-05-27]

### Bug Fixes

* improve logging to diagnose issues [1673a0f8](1673a0f80f483f78b778e9497ce8fc8c001f0da3)

## v0.16.1 [2021-05-26]

### Bug Fixes

* prevent transaction from being aborted when it's not abortable [fadda7df](fadda7df2eecdeb31c6416b118072eff3b289ce2)

## v0.16.0 [2021-05-21]

### Features

* edmc-5817: move helm chart to this repo [0b577607](0b577607b7202ed8242093aeb2badd1f3f4c2eb9)

## v0.15.0 [2021-05-21]

### Features

* EDMC-5179 Publish domain events to pulsar, introduce an in memory... [b45a1636](b45a1636bf29ecb8a3c04dc20163fcfa5eb35e10)

## v0.14.0 [2021-05-18]

### Features

* edmc-5817: remove appsettings file from container image [c86c9519](c86c95197c09e0e167ac817ed3387994e447a67c)

## v0.13.2 [2021-05-17]

### Bug Fixes

* ednc-5789: move configuration of producer to bootstrapper [2b123005](2b123005f0780c8723dd8fd964254f98ed9a5090)

## v0.13.1 [2021-05-17]

### Bug Fixes

* feat-5789: fixed null reference error for empty uploaded solutions, added component ids, fixed mongo class map registrations, and corrected solution ids. [ae85f22d](ae85f22d96981d05e6415125b13cced135f29724)

## v0.13.0 [2021-05-12]

### Features

* edmc-5789: remove redundant properties and add upload info so completeness of upload can be determined [fd91df56](fd91df56737c65e30a57ae0aab34808249290e37)

## v0.12.0 [2021-05-06]

### Features

* edmc-5789: persist multiple solutions [17a8ce72](17a8ce72b953437dc7ca70fe74e16dcc64882585)

## v0.11.3 [2021-05-06]

### Bug Fixes

* Feature/edmc 5169: Fix bug in message handler idempotency implementation [76bc0e8c](76bc0e8c5ea9de7708572027d6f97829d0e93855)

## v0.11.2 [2021-05-05]

### Patches

* Add solution idempotency and retry e2e tests plus remove some unused files [04160d82](04160d82804cf2706c0b54b7d2e793c6f1648a9a)

## v0.11.1 [2021-05-04]

### Patches

* Move common schema domain model into it's own library and move common domain abstractions to domain abstractions library [0f5738ad](0f5738adfacd1bb76535165b06a7197447a7b129)

## v0.11.0 [2021-04-29]

### Features

* edmc-5171: support multi-tenancy for solution persistence [e236da44](e236da4447e5e5d5c16806e36c8ed39dbfa185ee)

## v0.10.3 [2021-04-15]

### Patches

* Move common schema domain model into it's own library and move common domain abstractions to domain abstractions library [5b0d8548](5b0d8548787a16366c4aae8299e2700a17deda80)

## v0.10.2 [2021-04-15]

### Patches

* Feature/edmc 5169 Initial refactor to decouple messages from the domain models [4adb1689](4adb168933613a2ed68fbf46449ff8592a40545c)

## v0.10.1 [2021-04-15]

### Bug Fixes

* edmc-5230: fix (de)serialization of messages in design host and refactor [0b46c7e1](0b46c7e1a881fa6023c097f69fbe2dc0f275ab90)

## v0.10.0 [2021-04-14]

### Features

* edmc-5230: solution persist [96f470d4](96f470d47c1ad5c2d18027299d13f6e9f4d3983a)

## v0.9.1 [2021-03-22]

### Patches

* Correction to the description of IaC repo [0f280ecd](0f280ecde9f88c0021e959bad37f98fd990d17fe)
* Fix table on DeploymentModel.md [88929e36](88929e36b13d66bc450da9a356f9cf0265cbd088)
* Added Deployment model [ed2d2c51](ed2d2c51fd8624830fa17a0e28b202654a4c37e8)
* Update Architecture [08a28d32](08a28d3277fadd52136b7baeec9e1b038293f718)
* correction to formatting [a2c412c6](a2c412c6caed5d5981afa1e4893130874b71e21f)

## v0.9.0 [2021-03-18]

### Features

* enable avro serialisation for pulsar producer and consumer [3973ade5](3973ade5b4805ba4f389ff5b32e093ef54ad351b)

### Patches

* Improve test coverage [e84ef215](e84ef2151e3418923556ef4f5314999e1b718a28)
* Add IMessageSerialiser and ... [1fa99e92](1fa99e9202b1dc24d4b1482ccfcf4561c879e992)
* Remove redundant project references [c221dd31](c221dd311684edfbfec3da30bbb0eecd88e398f0)

## v0.8.2 [2021-03-16]

### Patches

* Corrections [376c1e3e](376c1e3e53cd56615265b773fc45f03b46a70db8)
* Added section on schema registry [68c125ba](68c125ba0b115b0b8ae94ed1dab87ebcb0375c01)
* Updated based on review comments... [79838fa8](79838fa8ac9a477df9b5b9d1f51340d47cc5193d)
* Remove "more to follow" from persistence section [4680deb3](4680deb3b21d069f2a6abc16ee3001404a2fb8bf)
* Formatting and typo corrections [32d068cf](32d068cf83e25115a3678b8f86c7bd939117e788)
* Update persistence section [e28fffae](e28fffae8e4bad47150b8c2e19f6157704e9d9bb)
* Documented the messaging infrastructure ... [260e1c36](260e1c36936cd07693748566fb09139cb9e3ebcd)
* remove expiry date from files [76835ef6](76835ef6c49ad7e56ec586dd457e8335634045e3)
* Add Saga description [f6c24f3d](f6c24f3dfe613f2ec7e91e18a507fa7e4f1b8106)
* Change saga image [8ce6657a](8ce6657ab0db7e05183a914a3e71dac6ca361424)
* Update to document index [cb271f4c](cb271f4c723024679d5ab39f018df29c0954ca23)
* Architecture docs for ACF [c1a739f7](c1a739f7b8f29bca926d5d30878891b4e1cb0193)

## v0.8.1 [2021-03-10]

### Patches

* EDMC-4915: clean up gitlab-c.yml file [aaafb77b](aaafb77b7b2ed7ac7e75b2de90b5f842c6cc6140)

## v0.8.0 [2021-03-03]

### Features

* updated outdated pulsar client to next major version [2950d6b1](2950d6b13679275caf51c007d718049a4728263d)
* add acl solution and build pipeline [5dec70f2](5dec70f279c54063641dfc082c869757af9d6631)
* AvroSchemaBinding can serialise complex object [3f452772](3f45277223e300c2c513c889a9627dbed5ba2007)
* Simplify Conductor schema [52478376](5247837661d8615bd5b6c4f257211ec85b15bb84)
* Serialise simple data record [a73f3b06](a73f3b06e406619c7582130cf4249d96f389d24a)
* mongo failure logging [79ef7211](79ef721110a665ee75c1ffd48bf55a3870a67448)
* add bloomberg source [dba37ca9](dba37ca9bad00ea4ed7b102c801c15fe5407110c)
* keying component [1411b99a](1411b99a1543fccae3da162f070af45e77cd0198)
* add initial rimes ingest component [7a1d7c3a](7a1d7c3a4b13917ddffa97583283bb5951b9c94a)
* bloomberg test which works in isolation, but not with other tests (wip) [bac8a06b](bac8a06b2bfca1c1c3acb7634ae1b909f527b1e9)
* filter component [95f8fbcd](95f8fbcdfea537d35733deb45a93bf58ac96bc8a)
* add mongo sink component with integration test [d74b9971](d74b997128280c1b907ec9ece5e2d8467d8524d4)
* (wip) typing component to type data from input file [25c96612](25c96612a59a12048e85b5393af86321f036aac6)
* allow bloomberg file component to append data from heading metadata [aa913d2d](aa913d2d7f346fc1e189932373d5b61e8b9328ea)
* add roslyn analyser to enforce style rules [283e9fb8](283e9fb885c17a78d489403e5c68eb740e395413)
* basic deduplication component [5c96a369](5c96a369f7e60e9f070def983b3552748defb72d)

### Bug Fixes

* fix versioning in master branch [b79bbc2a](b79bbc2af2a218694cb300735550933b51f12e6f)
* EDM-23610: remove reference to mongo package in domain project [1f4fcbc5](1f4fcbc55347098589b082b69a66718168a5be7a)
* build via changes to project settings and gitlab-ci [23985a6e](23985a6e2ca122feb020c62c50a1b9bec9a84cfe)
* remove folder [040d81c0](040d81c07e8766f78197d2dedfdf094e7315f949)
* pulsar tests [9cf5d8b8](9cf5d8b843129a3240ec78c677a0f651aaeee9f6)
* deduplication component test [64730827](6473082772d6f2cf7e121a4cc287cde9a883f9b5)
* add error logging [80ebab9f](80ebab9ff8a47eed9cf8fb0b36e3e84a72508bf6)
* filename [7d6c7790](7d6c7790b2b0092db93fe057fb22f467e246ad1d)
* use ihs docker repo [33e5c3ac](33e5c3aca7e457b733092058e857a694ee0ab335)
* formatting [07b32bc3](07b32bc389b18cb564dc5f365d948f6b6172b23e)
* warnings [8ecc2737](8ecc273706feddfa79e880a442e6b726632aba38)
* temporarily stop using async method [4f7ce490](4f7ce490b8c31adeed3ad1b91f14d8be2d05035a)
* add missing awaits [b62d36e0](b62d36e0d5d67aed8782bb36c996b8c088b10bb9)
* formatting [551d28ab](551d28ab08689cc749015c23945b42ee334d9ed0)
* formatting [6736f64f](6736f64f48ebed0a012b17c01b1be550efaeb037)
* remove schema method from component [4d32b724](4d32b72418d8f935971a46df07c5097c1404e442)
* strict build errors [539875e4](539875e48eb6cee32f8295f315efba1dc0159e3a)
* strict build errors [6150270b](6150270bea82839239c25563ea0a2951b567e154)
* strict build errors [4cb5b30f](4cb5b30f8bebfca06ad99c35e4df5feeefef3966)
* format errors via cli [e0cefd55](e0cefd5549dce605485ec5ebf8c0316f3ad9984a)
* make test wait until pulsar is ready [cc44f6f8](cc44f6f883d123344bfdd2737e2c4c87855a6d99)

### Patches

* Move integration tests into separate project [a146fefa](a146fefab3d444813e0a750f4ebe08d8c7a14c58)
* markdown doc generation and upload [c0bf9f23](c0bf9f23b4b61b92625411820b297cd532f10f1d)
* fix notice generation via gitlab-ci.yml rule for master [863112d5](863112d5ad77c7c9c007846c7369c6db4a419697)
* add dependencies fitness function [8accdf07](8accdf0724226330f16c446c90df094e519b4688)
* update packages highlighted by whitesource [129e9776](129e97765ced47c7bf613cf715e31ecbbddfbb61)
* add changelog generation [9909e01a](9909e01a4670bb6f7e0102a8afa1bcc118c18202)
* run stylcop analyzer across entire solution for ip compliance [d5c4ea1b](d5c4ea1b1da514c8cd87195fb623dad79d6bfe8c)
* Move application scoped tests out of Domain [137522f2](137522f22cff36da65762e350551d09041ffd3c6)
* add license file [558e5c00](558e5c00b2f0ff4a5f8f9fc9425a00dbf8a0e53b)
* Remove redundant project dependencies [32f3d124](32f3d124878a43365d5f28fab727e4e382983184)
* fix only:changes conditions which don't support variables [87c4579c](87c4579c04c8cf057236da051cb89729e98bf19f)
* suppress warnings [a990f664](a990f6641fa312d168effa55963e6f5a1c810b6c)
* fix formatting [b166cebb](b166cebbbfb8cfc366511a64bef669247aa4ec1e)
* suppress analyzer inspection of generated code [014dbc08](014dbc08da50a935f1a5672acd8462c5631c2baf)
* force pipeline to fail if there are build errors but the cli returns the wrong exit code [a4ebb26b](a4ebb26b52ff05680cb2d7233608651dbafb2641)
* gitlab ci file fix [2dd5886e](2dd5886e5f7e5e23a6125e5d85f708a8cf729155)
* Tidy up a few loose ends including fixing a saga bug, splitting aggregate events into separate stores [c9892f08](c9892f08d8c7d96409f45f5c7e8560d362471f5f)
* add acl sonarqube analysis [86021776](86021776d3721b6e00347abcf1f2e1f1d43f15da)
* sonarqube integration [b5d32765](b5d327659909a83ab911d6b3fe431340e0df9af6)
* update readme with test and versioning info [6de2f85f](6de2f85fb5a7a851a18b1887be0d60ed065cc2d5)
* allow intervention in semver calculation [518e17c1](518e17c17e73c074462095acd2269a6d9c5aef2a)
* Add run setting so integration tests can run lcoally [e016a013](e016a0137eeb030330b7fc72ece216e74ec64e75)
* add src folder [4857275e](4857275e953031fed496d60b562325883203ae68)
* move files [234d16f9](234d16f91885a9407b1b7e22d5845831c48db1bd)
* remove pointless arg from script [9be846fe](9be846fe3bc55f0c5e42fcaad49ee2292a338aa7)
* fix script [5d7739ba](5d7739baadfabd57f71c3a56d74bd3434d67dcc4)
* add version script and update ci [6ef89a4c](6ef89a4c7846745de2353b9891caa0e0d62c1132)
* add version script and update ci [21fb16e1](21fb16e16cf180ebb93ea04f85695611a709ebe7)
* Remove the Obsolete constraint for now [27d2733c](27d2733ca8c5f6648c51e47d945f6966957deedd)
* rename ISchemaMember to IPrimitiveSchema [00c8d179](00c8d179793a8e0822fbbfaf9684c7b2401f276d)
* fix pulsar config [23d30754](23d30754212ccb8157fcdde65d63f3fb5e8dce1c)
* formatting [2c1534b5](2c1534b5ef216e947666ee9db2916aadcabad2fe)
* add pulsar volume [be7097a1](be7097a1f81a830fc8ac1eec4c7129cb45d8cfc6)
* add source to bloomberg records correctly [ba29d98f](ba29d98fa4397a0586ca7a515591eb4fff480be2)
* add deduplicate component [e087b38d](e087b38dfc512325b8d614ad431881d05afb5c39)
* speculative fix [96d5adb4](96d5adb483e8e56031e1295ba60a4483b2eed23a)
* rename component to make its intent clearer [8e4fb59f](8e4fb59f2ac9f5a9afd1f5818246c192805af3c7)
* validation in bloomberg/rimes solution test [4bbc226a](4bbc226a0cdc1cc374647c69c50b6d56d360782f)
* rename component to clarify its purpose [94ce0bc6](94ce0bc61ecbceb8488cbc2d8bf22a9885e1aed7)
* Fix test [b8f6994c](b8f6994c04d98d26fdc4490c5916ffcd7966e574)
* wireup serilog to understand test failures [295d11a9](295d11a9e1e23352eb5b460a089bc6f10bfa8d4c)
* add more console output to diagnose issues in gitlab ci [73e77a60](73e77a6083fc313b5b4229c6ec3aef62a0f8a79e)
* add collection attribute to stop resource contention [c8a8d53c](c8a8d53cef5bde748d9686d110a0e9d44e54d0d9)
* working bloomberg and rimes solution (wipP [417e1a14](417e1a14d898ea49752a23ba8c5c3e4a1732c0da)
* up the assertion time [0a7bffc1](0a7bffc1d87dcd131633ee576ca732c758035f34)
* stop tests using same filename [21e20711](21e2071135dd683a083339ccb7370cd6d09b437c)
* speculative fix for mongo binding [cf5cb6ea](cf5cb6eacd4fdf1262da56b5696666e41d4c5b7a)
* file to class name [48d56ea7](48d56ea7ef4b0aa10b61711cbc2a01c6ebc3552e)
* fix connection string [c706f8b9](c706f8b9e5c396485b9455b53842ae1eb417f975)
* fix connection string [14956f5d](14956f5de54afd3df87062cc5c135610d4973961)
* speculative change to get integration tests running in pipeline [feb47246](feb47246dab25496c6568aa88ca7df8a3464bd5b)
* change test to use pulsar [7fc8d12d](7fc8d12d767ecd57ada6c6c8bf6423d07eed2f3b)
* add mongo sink solution [6241b57b](6241b57b44c90eea218b0384cd141c7534d95fd1)
* reduce duplicated LoC [37b9a56f](37b9a56f3e67a5228540b6ac6145ccc4eabf5464)
* add in-memory solution filter test [79864945](798649456d198fe8c5b613b8735333a217a844b9)
* resharper autofix to remove redundant code [135603a9](135603a90f1b86e8938eb015799e79d3fc396bd1)
* fixed initial bloomberg solution test [a1045e74](a1045e7404af233ddd00290809771ab94fef4f49)
* skip wip test [b9ff3488](b9ff348842e1880f5473350715547819fc50bab1)
* add logging to help understand the cause of test failures [e0578873](e0578873c0ea9020916363f3dfa7fb4c72fbcbc2)
* update readme with command for viewing warnings reliably locally [1e813d18](1e813d18b37869ecc797a275a7b22ac97fd86832)
* reorganise solution to accomodate more solution integration tests [744acc18](744acc18e49db0887c35d240bad0ce9dd1c56036)
* combine build and test to improve gitlab ci time [6432ce88](6432ce8890a45a7bddb2fcfe09e0d7636ce8b185)
* dotnet format instructions [1899fbeb](1899fbebcd98970779341ee27ade12db07731300)
* dotnet format autofixes [137c0660](137c066028745b2c566092fc89d7be14a9f96af4)
* improve clarity of readme [3a9226fe](3a9226feb180357e4b5adc04795d4a0c7c693427)
* add integration tests [039715e9](039715e996be33cc163cc5e93e183453ad549f79)
* Track record counts [884a468f](884a468f1fc4dbd7a7e716b882e042696c3a90a7)
* Further saga integration [7e3071f1](7e3071f17ef94a4581b2e53926394c8865a15233)
* Saga persistence [2fa0373f](2fa0373fab4ac6f87adc0534c22a6b681dfe9395)
* Improve log message [2d05e6d9](2d05e6d91c65abce3bdf3152cdf195c7617f67b1)

## v0.7.0-alpha.118+298b0a4 [2021-03-02]

### Features

* updated outdated pulsar client to next major version [2950d6b1](2950d6b13679275caf51c007d718049a4728263d)
* add acl solution and build pipeline [5dec70f2](5dec70f279c54063641dfc082c869757af9d6631)
* AvroSchemaBinding can serialise complex object [3f452772](3f45277223e300c2c513c889a9627dbed5ba2007)
* Simplify Conductor schema [52478376](5247837661d8615bd5b6c4f257211ec85b15bb84)
* Serialise simple data record [a73f3b06](a73f3b06e406619c7582130cf4249d96f389d24a)
* mongo failure logging [79ef7211](79ef721110a665ee75c1ffd48bf55a3870a67448)
* add bloomberg source [dba37ca9](dba37ca9bad00ea4ed7b102c801c15fe5407110c)
* keying component [1411b99a](1411b99a1543fccae3da162f070af45e77cd0198)
* add initial rimes ingest component [7a1d7c3a](7a1d7c3a4b13917ddffa97583283bb5951b9c94a)
* bloomberg test which works in isolation, but not with other tests (wip) [bac8a06b](bac8a06b2bfca1c1c3acb7634ae1b909f527b1e9)
* filter component [95f8fbcd](95f8fbcdfea537d35733deb45a93bf58ac96bc8a)
* add mongo sink component with integration test [d74b9971](d74b997128280c1b907ec9ece5e2d8467d8524d4)
* (wip) typing component to type data from input file [25c96612](25c96612a59a12048e85b5393af86321f036aac6)
* allow bloomberg file component to append data from heading metadata [aa913d2d](aa913d2d7f346fc1e189932373d5b61e8b9328ea)
* add roslyn analyser to enforce style rules [283e9fb8](283e9fb885c17a78d489403e5c68eb740e395413)
* basic deduplication component [5c96a369](5c96a369f7e60e9f070def983b3552748defb72d)

### Bug Fixes

* fix versioning in master branch [b79bbc2a](b79bbc2af2a218694cb300735550933b51f12e6f)
* EDM-23610: remove reference to mongo package in domain project [1f4fcbc5](1f4fcbc55347098589b082b69a66718168a5be7a)
* build via changes to project settings and gitlab-ci [23985a6e](23985a6e2ca122feb020c62c50a1b9bec9a84cfe)
* remove folder [040d81c0](040d81c07e8766f78197d2dedfdf094e7315f949)
* pulsar tests [9cf5d8b8](9cf5d8b843129a3240ec78c677a0f651aaeee9f6)
* deduplication component test [64730827](6473082772d6f2cf7e121a4cc287cde9a883f9b5)
* add error logging [80ebab9f](80ebab9ff8a47eed9cf8fb0b36e3e84a72508bf6)
* filename [7d6c7790](7d6c7790b2b0092db93fe057fb22f467e246ad1d)
* use ihs docker repo [33e5c3ac](33e5c3aca7e457b733092058e857a694ee0ab335)
* formatting [07b32bc3](07b32bc389b18cb564dc5f365d948f6b6172b23e)
* warnings [8ecc2737](8ecc273706feddfa79e880a442e6b726632aba38)
* temporarily stop using async method [4f7ce490](4f7ce490b8c31adeed3ad1b91f14d8be2d05035a)
* add missing awaits [b62d36e0](b62d36e0d5d67aed8782bb36c996b8c088b10bb9)
* formatting [551d28ab](551d28ab08689cc749015c23945b42ee334d9ed0)
* formatting [6736f64f](6736f64f48ebed0a012b17c01b1be550efaeb037)
* remove schema method from component [4d32b724](4d32b72418d8f935971a46df07c5097c1404e442)
* strict build errors [539875e4](539875e48eb6cee32f8295f315efba1dc0159e3a)
* strict build errors [6150270b](6150270bea82839239c25563ea0a2951b567e154)
* strict build errors [4cb5b30f](4cb5b30f8bebfca06ad99c35e4df5feeefef3966)
* format errors via cli [e0cefd55](e0cefd5549dce605485ec5ebf8c0316f3ad9984a)
* make test wait until pulsar is ready [cc44f6f8](cc44f6f883d123344bfdd2737e2c4c87855a6d99)

### Patches

* allow change log generation to run locally [d3228bb3](d3228bb38c77713793088c3e843abaf02689e445)
* allow generation of docs locally [5fb3cfa9](5fb3cfa96be65041cfa5246ff0aed52a00847b45)
* move jobs into locally runable scripts [263aeaf8](263aeaf8c4a744f0ccd1827a8d650a6591e1f1e9)
* fix job naming consistency [c9a26d9b](c9a26d9b50e51d725d29da0f0f43f5b6fef81f72)
* markdown doc generation and upload [c0bf9f23](c0bf9f23b4b61b92625411820b297cd532f10f1d)
* fix notice generation via gitlab-ci.yml rule for master [863112d5](863112d5ad77c7c9c007846c7369c6db4a419697)
* add dependencies fitness function [8accdf07](8accdf0724226330f16c446c90df094e519b4688)
* update packages highlighted by whitesource [129e9776](129e97765ced47c7bf613cf715e31ecbbddfbb61)
* add changelog generation [9909e01a](9909e01a4670bb6f7e0102a8afa1bcc118c18202)
* run stylcop analyzer across entire solution for ip compliance [d5c4ea1b](d5c4ea1b1da514c8cd87195fb623dad79d6bfe8c)
* Move application scoped tests out of Domain [137522f2](137522f22cff36da65762e350551d09041ffd3c6)
* add license file [558e5c00](558e5c00b2f0ff4a5f8f9fc9425a00dbf8a0e53b)
* Remove redundant project dependencies [32f3d124](32f3d124878a43365d5f28fab727e4e382983184)
* fix only:changes conditions which don't support variables [87c4579c](87c4579c04c8cf057236da051cb89729e98bf19f)
* suppress warnings [a990f664](a990f6641fa312d168effa55963e6f5a1c810b6c)
* fix formatting [b166cebb](b166cebbbfb8cfc366511a64bef669247aa4ec1e)
* suppress analyzer inspection of generated code [014dbc08](014dbc08da50a935f1a5672acd8462c5631c2baf)
* force pipeline to fail if there are build errors but the cli returns the wrong exit code [a4ebb26b](a4ebb26b52ff05680cb2d7233608651dbafb2641)
* gitlab ci file fix [2dd5886e](2dd5886e5f7e5e23a6125e5d85f708a8cf729155)
* Tidy up a few loose ends including fixing a saga bug, splitting aggregate events into separate stores [c9892f08](c9892f08d8c7d96409f45f5c7e8560d362471f5f)
* add acl sonarqube analysis [86021776](86021776d3721b6e00347abcf1f2e1f1d43f15da)
* sonarqube integration [b5d32765](b5d327659909a83ab911d6b3fe431340e0df9af6)
* update readme with test and versioning info [6de2f85f](6de2f85fb5a7a851a18b1887be0d60ed065cc2d5)
* allow intervention in semver calculation [518e17c1](518e17c17e73c074462095acd2269a6d9c5aef2a)
* Add run setting so integration tests can run lcoally [e016a013](e016a0137eeb030330b7fc72ece216e74ec64e75)
* add src folder [4857275e](4857275e953031fed496d60b562325883203ae68)
* move files [234d16f9](234d16f91885a9407b1b7e22d5845831c48db1bd)
* remove pointless arg from script [9be846fe](9be846fe3bc55f0c5e42fcaad49ee2292a338aa7)
* fix script [5d7739ba](5d7739baadfabd57f71c3a56d74bd3434d67dcc4)
* add version script and update ci [6ef89a4c](6ef89a4c7846745de2353b9891caa0e0d62c1132)
* add version script and update ci [21fb16e1](21fb16e16cf180ebb93ea04f85695611a709ebe7)
* Remove the Obsolete constraint for now [27d2733c](27d2733ca8c5f6648c51e47d945f6966957deedd)
* rename ISchemaMember to IPrimitiveSchema [00c8d179](00c8d179793a8e0822fbbfaf9684c7b2401f276d)
* fix pulsar config [23d30754](23d30754212ccb8157fcdde65d63f3fb5e8dce1c)
* formatting [2c1534b5](2c1534b5ef216e947666ee9db2916aadcabad2fe)
* add pulsar volume [be7097a1](be7097a1f81a830fc8ac1eec4c7129cb45d8cfc6)
* add source to bloomberg records correctly [ba29d98f](ba29d98fa4397a0586ca7a515591eb4fff480be2)
* add deduplicate component [e087b38d](e087b38dfc512325b8d614ad431881d05afb5c39)
* speculative fix [96d5adb4](96d5adb483e8e56031e1295ba60a4483b2eed23a)
* rename component to make its intent clearer [8e4fb59f](8e4fb59f2ac9f5a9afd1f5818246c192805af3c7)
* validation in bloomberg/rimes solution test [4bbc226a](4bbc226a0cdc1cc374647c69c50b6d56d360782f)
* rename component to clarify its purpose [94ce0bc6](94ce0bc61ecbceb8488cbc2d8bf22a9885e1aed7)
* Fix test [b8f6994c](b8f6994c04d98d26fdc4490c5916ffcd7966e574)
* wireup serilog to understand test failures [295d11a9](295d11a9e1e23352eb5b460a089bc6f10bfa8d4c)
* add more console output to diagnose issues in gitlab ci [73e77a60](73e77a6083fc313b5b4229c6ec3aef62a0f8a79e)
* add collection attribute to stop resource contention [c8a8d53c](c8a8d53cef5bde748d9686d110a0e9d44e54d0d9)
* working bloomberg and rimes solution (wipP [417e1a14](417e1a14d898ea49752a23ba8c5c3e4a1732c0da)
* up the assertion time [0a7bffc1](0a7bffc1d87dcd131633ee576ca732c758035f34)
* stop tests using same filename [21e20711](21e2071135dd683a083339ccb7370cd6d09b437c)
* speculative fix for mongo binding [cf5cb6ea](cf5cb6eacd4fdf1262da56b5696666e41d4c5b7a)
* file to class name [48d56ea7](48d56ea7ef4b0aa10b61711cbc2a01c6ebc3552e)
* fix connection string [c706f8b9](c706f8b9e5c396485b9455b53842ae1eb417f975)
* fix connection string [14956f5d](14956f5de54afd3df87062cc5c135610d4973961)
* speculative change to get integration tests running in pipeline [feb47246](feb47246dab25496c6568aa88ca7df8a3464bd5b)
* change test to use pulsar [7fc8d12d](7fc8d12d767ecd57ada6c6c8bf6423d07eed2f3b)
* add mongo sink solution [6241b57b](6241b57b44c90eea218b0384cd141c7534d95fd1)
* reduce duplicated LoC [37b9a56f](37b9a56f3e67a5228540b6ac6145ccc4eabf5464)
* add in-memory solution filter test [79864945](798649456d198fe8c5b613b8735333a217a844b9)
* resharper autofix to remove redundant code [135603a9](135603a90f1b86e8938eb015799e79d3fc396bd1)
* fixed initial bloomberg solution test [a1045e74](a1045e7404af233ddd00290809771ab94fef4f49)
* skip wip test [b9ff3488](b9ff348842e1880f5473350715547819fc50bab1)
* add logging to help understand the cause of test failures [e0578873](e0578873c0ea9020916363f3dfa7fb4c72fbcbc2)
* update readme with command for viewing warnings reliably locally [1e813d18](1e813d18b37869ecc797a275a7b22ac97fd86832)
* reorganise solution to accomodate more solution integration tests [744acc18](744acc18e49db0887c35d240bad0ce9dd1c56036)
* combine build and test to improve gitlab ci time [6432ce88](6432ce8890a45a7bddb2fcfe09e0d7636ce8b185)
* dotnet format instructions [1899fbeb](1899fbebcd98970779341ee27ade12db07731300)
* dotnet format autofixes [137c0660](137c066028745b2c566092fc89d7be14a9f96af4)
* improve clarity of readme [3a9226fe](3a9226feb180357e4b5adc04795d4a0c7c693427)
* add integration tests [039715e9](039715e996be33cc163cc5e93e183453ad549f79)
* Track record counts [884a468f](884a468f1fc4dbd7a7e716b882e042696c3a90a7)
* Further saga integration [7e3071f1](7e3071f17ef94a4581b2e53926394c8865a15233)
* Saga persistence [2fa0373f](2fa0373fab4ac6f87adc0534c22a6b681dfe9395)
* Improve log message [2d05e6d9](2d05e6d91c65abce3bdf3152cdf195c7617f67b1)

## v0.6.4-alpha.14+3135ba8 [2021-03-02]

### Patches

* allow generation of docs locally [02373c82](02373c8239be22c16619b50477aa0d2c3699dddf)
* move jobs into locally runable scripts [f891ae55](f891ae55c7a37b6e1a2976e2f6002d2743b4cfc3)
* fix job naming consistency [c9a26d9b](c9a26d9b50e51d725d29da0f0f43f5b6fef81f72)

## v0.6.3 [2021-02-24]

### Patches

* markdown doc generation and upload [c0bf9f23](c0bf9f23b4b61b92625411820b297cd532f10f1d)

## v0.6.2 [2021-02-23]

### Patches

* fix notice generation via gitlab-ci.yml rule for master [863112d5](863112d5ad77c7c9c007846c7369c6db4a419697)

## v0.6.1 [2021-02-23]

### Patches

* add dependencies fitness function [8accdf07](8accdf0724226330f16c446c90df094e519b4688)

## v0.6.0 [2021-02-23]

### Features

* updated outdated pulsar client to next major version [2950d6b1](2950d6b13679275caf51c007d718049a4728263d)
* add acl solution and build pipeline [5dec70f2](5dec70f279c54063641dfc082c869757af9d6631)
* AvroSchemaBinding can serialise complex object [3f452772](3f45277223e300c2c513c889a9627dbed5ba2007)
* Simplify Conductor schema [52478376](5247837661d8615bd5b6c4f257211ec85b15bb84)
* Serialise simple data record [a73f3b06](a73f3b06e406619c7582130cf4249d96f389d24a)
* mongo failure logging [79ef7211](79ef721110a665ee75c1ffd48bf55a3870a67448)
* add bloomberg source [dba37ca9](dba37ca9bad00ea4ed7b102c801c15fe5407110c)
* keying component [1411b99a](1411b99a1543fccae3da162f070af45e77cd0198)
* add initial rimes ingest component [7a1d7c3a](7a1d7c3a4b13917ddffa97583283bb5951b9c94a)
* bloomberg test which works in isolation, but not with other tests (wip) [bac8a06b](bac8a06b2bfca1c1c3acb7634ae1b909f527b1e9)
* filter component [95f8fbcd](95f8fbcdfea537d35733deb45a93bf58ac96bc8a)
* add mongo sink component with integration test [d74b9971](d74b997128280c1b907ec9ece5e2d8467d8524d4)
* (wip) typing component to type data from input file [25c96612](25c96612a59a12048e85b5393af86321f036aac6)
* allow bloomberg file component to append data from heading metadata [aa913d2d](aa913d2d7f346fc1e189932373d5b61e8b9328ea)
* add roslyn analyser to enforce style rules [283e9fb8](283e9fb885c17a78d489403e5c68eb740e395413)
* basic deduplication component [5c96a369](5c96a369f7e60e9f070def983b3552748defb72d)

### Bug Fixes

* fix versioning in master branch [b79bbc2a](b79bbc2af2a218694cb300735550933b51f12e6f)
* EDM-23610: remove reference to mongo package in domain project [1f4fcbc5](1f4fcbc55347098589b082b69a66718168a5be7a)
* build via changes to project settings and gitlab-ci [23985a6e](23985a6e2ca122feb020c62c50a1b9bec9a84cfe)
* remove folder [040d81c0](040d81c07e8766f78197d2dedfdf094e7315f949)
* pulsar tests [9cf5d8b8](9cf5d8b843129a3240ec78c677a0f651aaeee9f6)
* deduplication component test [64730827](6473082772d6f2cf7e121a4cc287cde9a883f9b5)
* add error logging [80ebab9f](80ebab9ff8a47eed9cf8fb0b36e3e84a72508bf6)
* filename [7d6c7790](7d6c7790b2b0092db93fe057fb22f467e246ad1d)
* use ihs docker repo [33e5c3ac](33e5c3aca7e457b733092058e857a694ee0ab335)
* formatting [07b32bc3](07b32bc389b18cb564dc5f365d948f6b6172b23e)
* warnings [8ecc2737](8ecc273706feddfa79e880a442e6b726632aba38)
* temporarily stop using async method [4f7ce490](4f7ce490b8c31adeed3ad1b91f14d8be2d05035a)
* add missing awaits [b62d36e0](b62d36e0d5d67aed8782bb36c996b8c088b10bb9)
* formatting [551d28ab](551d28ab08689cc749015c23945b42ee334d9ed0)
* formatting [6736f64f](6736f64f48ebed0a012b17c01b1be550efaeb037)
* remove schema method from component [4d32b724](4d32b72418d8f935971a46df07c5097c1404e442)
* strict build errors [539875e4](539875e48eb6cee32f8295f315efba1dc0159e3a)
* strict build errors [6150270b](6150270bea82839239c25563ea0a2951b567e154)
* strict build errors [4cb5b30f](4cb5b30f8bebfca06ad99c35e4df5feeefef3966)
* format errors via cli [e0cefd55](e0cefd5549dce605485ec5ebf8c0316f3ad9984a)
* make test wait until pulsar is ready [cc44f6f8](cc44f6f883d123344bfdd2737e2c4c87855a6d99)

### Patches

* update packages highlighted by whitesource [129e9776](129e97765ced47c7bf613cf715e31ecbbddfbb61)
* add changelog generation [9909e01a](9909e01a4670bb6f7e0102a8afa1bcc118c18202)
* run stylcop analyzer across entire solution for ip compliance [d5c4ea1b](d5c4ea1b1da514c8cd87195fb623dad79d6bfe8c)
* Move application scoped tests out of Domain [137522f2](137522f22cff36da65762e350551d09041ffd3c6)
* add license file [558e5c00](558e5c00b2f0ff4a5f8f9fc9425a00dbf8a0e53b)
* Remove redundant project dependencies [32f3d124](32f3d124878a43365d5f28fab727e4e382983184)
* fix only:changes conditions which don't support variables [87c4579c](87c4579c04c8cf057236da051cb89729e98bf19f)
* suppress warnings [a990f664](a990f6641fa312d168effa55963e6f5a1c810b6c)
* fix formatting [b166cebb](b166cebbbfb8cfc366511a64bef669247aa4ec1e)
* suppress analyzer inspection of generated code [014dbc08](014dbc08da50a935f1a5672acd8462c5631c2baf)
* force pipeline to fail if there are build errors but the cli returns the wrong exit code [a4ebb26b](a4ebb26b52ff05680cb2d7233608651dbafb2641)
* gitlab ci file fix [2dd5886e](2dd5886e5f7e5e23a6125e5d85f708a8cf729155)
* Tidy up a few loose ends including fixing a saga bug, splitting aggregate events into separate stores [c9892f08](c9892f08d8c7d96409f45f5c7e8560d362471f5f)
* add acl sonarqube analysis [86021776](86021776d3721b6e00347abcf1f2e1f1d43f15da)
* sonarqube integration [b5d32765](b5d327659909a83ab911d6b3fe431340e0df9af6)
* update readme with test and versioning info [6de2f85f](6de2f85fb5a7a851a18b1887be0d60ed065cc2d5)
* allow intervention in semver calculation [518e17c1](518e17c17e73c074462095acd2269a6d9c5aef2a)
* Add run setting so integration tests can run lcoally [e016a013](e016a0137eeb030330b7fc72ece216e74ec64e75)
* add src folder [4857275e](4857275e953031fed496d60b562325883203ae68)
* move files [234d16f9](234d16f91885a9407b1b7e22d5845831c48db1bd)
* remove pointless arg from script [9be846fe](9be846fe3bc55f0c5e42fcaad49ee2292a338aa7)
* fix script [5d7739ba](5d7739baadfabd57f71c3a56d74bd3434d67dcc4)
* add version script and update ci [6ef89a4c](6ef89a4c7846745de2353b9891caa0e0d62c1132)
* add version script and update ci [21fb16e1](21fb16e16cf180ebb93ea04f85695611a709ebe7)
* Remove the Obsolete constraint for now [27d2733c](27d2733ca8c5f6648c51e47d945f6966957deedd)
* rename ISchemaMember to IPrimitiveSchema [00c8d179](00c8d179793a8e0822fbbfaf9684c7b2401f276d)
* fix pulsar config [23d30754](23d30754212ccb8157fcdde65d63f3fb5e8dce1c)
* formatting [2c1534b5](2c1534b5ef216e947666ee9db2916aadcabad2fe)
* add pulsar volume [be7097a1](be7097a1f81a830fc8ac1eec4c7129cb45d8cfc6)
* add source to bloomberg records correctly [ba29d98f](ba29d98fa4397a0586ca7a515591eb4fff480be2)
* add deduplicate component [e087b38d](e087b38dfc512325b8d614ad431881d05afb5c39)
* speculative fix [96d5adb4](96d5adb483e8e56031e1295ba60a4483b2eed23a)
* rename component to make its intent clearer [8e4fb59f](8e4fb59f2ac9f5a9afd1f5818246c192805af3c7)
* validation in bloomberg/rimes solution test [4bbc226a](4bbc226a0cdc1cc374647c69c50b6d56d360782f)
* rename component to clarify its purpose [94ce0bc6](94ce0bc61ecbceb8488cbc2d8bf22a9885e1aed7)
* Fix test [b8f6994c](b8f6994c04d98d26fdc4490c5916ffcd7966e574)
* wireup serilog to understand test failures [295d11a9](295d11a9e1e23352eb5b460a089bc6f10bfa8d4c)
* add more console output to diagnose issues in gitlab ci [73e77a60](73e77a6083fc313b5b4229c6ec3aef62a0f8a79e)
* add collection attribute to stop resource contention [c8a8d53c](c8a8d53cef5bde748d9686d110a0e9d44e54d0d9)
* working bloomberg and rimes solution (wipP [417e1a14](417e1a14d898ea49752a23ba8c5c3e4a1732c0da)
* up the assertion time [0a7bffc1](0a7bffc1d87dcd131633ee576ca732c758035f34)
* stop tests using same filename [21e20711](21e2071135dd683a083339ccb7370cd6d09b437c)
* speculative fix for mongo binding [cf5cb6ea](cf5cb6eacd4fdf1262da56b5696666e41d4c5b7a)
* file to class name [48d56ea7](48d56ea7ef4b0aa10b61711cbc2a01c6ebc3552e)
* fix connection string [c706f8b9](c706f8b9e5c396485b9455b53842ae1eb417f975)
* fix connection string [14956f5d](14956f5de54afd3df87062cc5c135610d4973961)
* speculative change to get integration tests running in pipeline [feb47246](feb47246dab25496c6568aa88ca7df8a3464bd5b)
* change test to use pulsar [7fc8d12d](7fc8d12d767ecd57ada6c6c8bf6423d07eed2f3b)
* add mongo sink solution [6241b57b](6241b57b44c90eea218b0384cd141c7534d95fd1)
* reduce duplicated LoC [37b9a56f](37b9a56f3e67a5228540b6ac6145ccc4eabf5464)
* add in-memory solution filter test [79864945](798649456d198fe8c5b613b8735333a217a844b9)
* resharper autofix to remove redundant code [135603a9](135603a90f1b86e8938eb015799e79d3fc396bd1)
* fixed initial bloomberg solution test [a1045e74](a1045e7404af233ddd00290809771ab94fef4f49)
* skip wip test [b9ff3488](b9ff348842e1880f5473350715547819fc50bab1)
* add logging to help understand the cause of test failures [e0578873](e0578873c0ea9020916363f3dfa7fb4c72fbcbc2)
* update readme with command for viewing warnings reliably locally [1e813d18](1e813d18b37869ecc797a275a7b22ac97fd86832)
* reorganise solution to accomodate more solution integration tests [744acc18](744acc18e49db0887c35d240bad0ce9dd1c56036)
* combine build and test to improve gitlab ci time [6432ce88](6432ce8890a45a7bddb2fcfe09e0d7636ce8b185)
* dotnet format instructions [1899fbeb](1899fbebcd98970779341ee27ade12db07731300)
* dotnet format autofixes [137c0660](137c066028745b2c566092fc89d7be14a9f96af4)
* improve clarity of readme [3a9226fe](3a9226feb180357e4b5adc04795d4a0c7c693427)
* add integration tests [039715e9](039715e996be33cc163cc5e93e183453ad549f79)
* Track record counts [884a468f](884a468f1fc4dbd7a7e716b882e042696c3a90a7)
* Further saga integration [7e3071f1](7e3071f17ef94a4581b2e53926394c8865a15233)
* Saga persistence [2fa0373f](2fa0373fab4ac6f87adc0534c22a6b681dfe9395)
* Improve log message [2d05e6d9](2d05e6d91c65abce3bdf3152cdf195c7617f67b1)

## v0.5.1 [2021-02-23]

### Bug Fixes

* speculative fix for versions in master branch [f832e008](f832e00861e49f9d0017a52d215b5689e35905fa)

## v0.5.0+2950d6b1 [2021-02-23]

### Features

* updated outdated pulsar client to next major version [2950d6b1](2950d6b13679275caf51c007d718049a4728263d)
* add acl solution and build pipeline [5dec70f2](5dec70f279c54063641dfc082c869757af9d6631)
* AvroSchemaBinding can serialise complex object [3f452772](3f45277223e300c2c513c889a9627dbed5ba2007)
* Simplify Conductor schema [52478376](5247837661d8615bd5b6c4f257211ec85b15bb84)
* Serialise simple data record [a73f3b06](a73f3b06e406619c7582130cf4249d96f389d24a)
* mongo failure logging [79ef7211](79ef721110a665ee75c1ffd48bf55a3870a67448)
* add bloomberg source [dba37ca9](dba37ca9bad00ea4ed7b102c801c15fe5407110c)
* keying component [1411b99a](1411b99a1543fccae3da162f070af45e77cd0198)
* add initial rimes ingest component [7a1d7c3a](7a1d7c3a4b13917ddffa97583283bb5951b9c94a)
* bloomberg test which works in isolation, but not with other tests (wip) [bac8a06b](bac8a06b2bfca1c1c3acb7634ae1b909f527b1e9)
* filter component [95f8fbcd](95f8fbcdfea537d35733deb45a93bf58ac96bc8a)
* add mongo sink component with integration test [d74b9971](d74b997128280c1b907ec9ece5e2d8467d8524d4)
* (wip) typing component to type data from input file [25c96612](25c96612a59a12048e85b5393af86321f036aac6)
* allow bloomberg file component to append data from heading metadata [aa913d2d](aa913d2d7f346fc1e189932373d5b61e8b9328ea)
* add roslyn analyser to enforce style rules [283e9fb8](283e9fb885c17a78d489403e5c68eb740e395413)
* basic deduplication component [5c96a369](5c96a369f7e60e9f070def983b3552748defb72d)

### Bug Fixes

* EDM-23610: remove reference to mongo package in domain project [1f4fcbc5](1f4fcbc55347098589b082b69a66718168a5be7a)
* build via changes to project settings and gitlab-ci [23985a6e](23985a6e2ca122feb020c62c50a1b9bec9a84cfe)
* remove folder [040d81c0](040d81c07e8766f78197d2dedfdf094e7315f949)
* pulsar tests [9cf5d8b8](9cf5d8b843129a3240ec78c677a0f651aaeee9f6)
* deduplication component test [64730827](6473082772d6f2cf7e121a4cc287cde9a883f9b5)
* add error logging [80ebab9f](80ebab9ff8a47eed9cf8fb0b36e3e84a72508bf6)
* filename [7d6c7790](7d6c7790b2b0092db93fe057fb22f467e246ad1d)
* use ihs docker repo [33e5c3ac](33e5c3aca7e457b733092058e857a694ee0ab335)
* formatting [07b32bc3](07b32bc389b18cb564dc5f365d948f6b6172b23e)
* warnings [8ecc2737](8ecc273706feddfa79e880a442e6b726632aba38)
* temporarily stop using async method [4f7ce490](4f7ce490b8c31adeed3ad1b91f14d8be2d05035a)
* add missing awaits [b62d36e0](b62d36e0d5d67aed8782bb36c996b8c088b10bb9)
* formatting [551d28ab](551d28ab08689cc749015c23945b42ee334d9ed0)
* formatting [6736f64f](6736f64f48ebed0a012b17c01b1be550efaeb037)
* remove schema method from component [4d32b724](4d32b72418d8f935971a46df07c5097c1404e442)
* strict build errors [539875e4](539875e48eb6cee32f8295f315efba1dc0159e3a)
* strict build errors [6150270b](6150270bea82839239c25563ea0a2951b567e154)
* strict build errors [4cb5b30f](4cb5b30f8bebfca06ad99c35e4df5feeefef3966)
* format errors via cli [e0cefd55](e0cefd5549dce605485ec5ebf8c0316f3ad9984a)
* make test wait until pulsar is ready [cc44f6f8](cc44f6f883d123344bfdd2737e2c4c87855a6d99)

### Patches

* update packages highlighted by whitesource [129e9776](129e97765ced47c7bf613cf715e31ecbbddfbb61)
* add changelog generation [9909e01a](9909e01a4670bb6f7e0102a8afa1bcc118c18202)
* run stylcop analyzer across entire solution for ip compliance [d5c4ea1b](d5c4ea1b1da514c8cd87195fb623dad79d6bfe8c)
* Move application scoped tests out of Domain [137522f2](137522f22cff36da65762e350551d09041ffd3c6)
* add license file [558e5c00](558e5c00b2f0ff4a5f8f9fc9425a00dbf8a0e53b)
* Remove redundant project dependencies [32f3d124](32f3d124878a43365d5f28fab727e4e382983184)
* fix only:changes conditions which don't support variables [87c4579c](87c4579c04c8cf057236da051cb89729e98bf19f)
* suppress warnings [a990f664](a990f6641fa312d168effa55963e6f5a1c810b6c)
* fix formatting [b166cebb](b166cebbbfb8cfc366511a64bef669247aa4ec1e)
* suppress analyzer inspection of generated code [014dbc08](014dbc08da50a935f1a5672acd8462c5631c2baf)
* force pipeline to fail if there are build errors but the cli returns the wrong exit code [a4ebb26b](a4ebb26b52ff05680cb2d7233608651dbafb2641)
* gitlab ci file fix [2dd5886e](2dd5886e5f7e5e23a6125e5d85f708a8cf729155)
* Tidy up a few loose ends including fixing a saga bug, splitting aggregate events into separate stores [c9892f08](c9892f08d8c7d96409f45f5c7e8560d362471f5f)
* add acl sonarqube analysis [86021776](86021776d3721b6e00347abcf1f2e1f1d43f15da)
* sonarqube integration [b5d32765](b5d327659909a83ab911d6b3fe431340e0df9af6)
* update readme with test and versioning info [6de2f85f](6de2f85fb5a7a851a18b1887be0d60ed065cc2d5)
* allow intervention in semver calculation [518e17c1](518e17c17e73c074462095acd2269a6d9c5aef2a)
* Add run setting so integration tests can run lcoally [e016a013](e016a0137eeb030330b7fc72ece216e74ec64e75)
* add src folder [4857275e](4857275e953031fed496d60b562325883203ae68)
* move files [234d16f9](234d16f91885a9407b1b7e22d5845831c48db1bd)
* remove pointless arg from script [9be846fe](9be846fe3bc55f0c5e42fcaad49ee2292a338aa7)
* fix script [5d7739ba](5d7739baadfabd57f71c3a56d74bd3434d67dcc4)
* add version script and update ci [6ef89a4c](6ef89a4c7846745de2353b9891caa0e0d62c1132)
* add version script and update ci [21fb16e1](21fb16e16cf180ebb93ea04f85695611a709ebe7)
* Remove the Obsolete constraint for now [27d2733c](27d2733ca8c5f6648c51e47d945f6966957deedd)
* rename ISchemaMember to IPrimitiveSchema [00c8d179](00c8d179793a8e0822fbbfaf9684c7b2401f276d)
* fix pulsar config [23d30754](23d30754212ccb8157fcdde65d63f3fb5e8dce1c)
* formatting [2c1534b5](2c1534b5ef216e947666ee9db2916aadcabad2fe)
* add pulsar volume [be7097a1](be7097a1f81a830fc8ac1eec4c7129cb45d8cfc6)
* add source to bloomberg records correctly [ba29d98f](ba29d98fa4397a0586ca7a515591eb4fff480be2)
* add deduplicate component [e087b38d](e087b38dfc512325b8d614ad431881d05afb5c39)
* speculative fix [96d5adb4](96d5adb483e8e56031e1295ba60a4483b2eed23a)
* rename component to make its intent clearer [8e4fb59f](8e4fb59f2ac9f5a9afd1f5818246c192805af3c7)
* validation in bloomberg/rimes solution test [4bbc226a](4bbc226a0cdc1cc374647c69c50b6d56d360782f)
* rename component to clarify its purpose [94ce0bc6](94ce0bc61ecbceb8488cbc2d8bf22a9885e1aed7)
* Fix test [b8f6994c](b8f6994c04d98d26fdc4490c5916ffcd7966e574)
* wireup serilog to understand test failures [295d11a9](295d11a9e1e23352eb5b460a089bc6f10bfa8d4c)
* add more console output to diagnose issues in gitlab ci [73e77a60](73e77a6083fc313b5b4229c6ec3aef62a0f8a79e)
* add collection attribute to stop resource contention [c8a8d53c](c8a8d53cef5bde748d9686d110a0e9d44e54d0d9)
* working bloomberg and rimes solution (wipP [417e1a14](417e1a14d898ea49752a23ba8c5c3e4a1732c0da)
* up the assertion time [0a7bffc1](0a7bffc1d87dcd131633ee576ca732c758035f34)
* stop tests using same filename [21e20711](21e2071135dd683a083339ccb7370cd6d09b437c)
* speculative fix for mongo binding [cf5cb6ea](cf5cb6eacd4fdf1262da56b5696666e41d4c5b7a)
* file to class name [48d56ea7](48d56ea7ef4b0aa10b61711cbc2a01c6ebc3552e)
* fix connection string [c706f8b9](c706f8b9e5c396485b9455b53842ae1eb417f975)
* fix connection string [14956f5d](14956f5de54afd3df87062cc5c135610d4973961)
* speculative change to get integration tests running in pipeline [feb47246](feb47246dab25496c6568aa88ca7df8a3464bd5b)
* change test to use pulsar [7fc8d12d](7fc8d12d767ecd57ada6c6c8bf6423d07eed2f3b)
* add mongo sink solution [6241b57b](6241b57b44c90eea218b0384cd141c7534d95fd1)
* reduce duplicated LoC [37b9a56f](37b9a56f3e67a5228540b6ac6145ccc4eabf5464)
* add in-memory solution filter test [79864945](798649456d198fe8c5b613b8735333a217a844b9)
* resharper autofix to remove redundant code [135603a9](135603a90f1b86e8938eb015799e79d3fc396bd1)
* fixed initial bloomberg solution test [a1045e74](a1045e7404af233ddd00290809771ab94fef4f49)
* skip wip test [b9ff3488](b9ff348842e1880f5473350715547819fc50bab1)
* add logging to help understand the cause of test failures [e0578873](e0578873c0ea9020916363f3dfa7fb4c72fbcbc2)
* update readme with command for viewing warnings reliably locally [1e813d18](1e813d18b37869ecc797a275a7b22ac97fd86832)
* reorganise solution to accomodate more solution integration tests [744acc18](744acc18e49db0887c35d240bad0ce9dd1c56036)
* combine build and test to improve gitlab ci time [6432ce88](6432ce8890a45a7bddb2fcfe09e0d7636ce8b185)
* dotnet format instructions [1899fbeb](1899fbebcd98970779341ee27ade12db07731300)
* dotnet format autofixes [137c0660](137c066028745b2c566092fc89d7be14a9f96af4)
* improve clarity of readme [3a9226fe](3a9226feb180357e4b5adc04795d4a0c7c693427)
* add integration tests [039715e9](039715e996be33cc163cc5e93e183453ad549f79)
* Track record counts [884a468f](884a468f1fc4dbd7a7e716b882e042696c3a90a7)
* Further saga integration [7e3071f1](7e3071f17ef94a4581b2e53926394c8865a15233)
* Saga persistence [2fa0373f](2fa0373fab4ac6f87adc0534c22a6b681dfe9395)
* Improve log message [2d05e6d9](2d05e6d91c65abce3bdf3152cdf195c7617f67b1)


## v0.3.0-alpha.109+199b8cb3 [2021-02-22]

### Features

* updated outdated pulsar client to next major version [b81091c4](b81091c40523951182cfadc47e8530e919620c45)
* remove acl [fff0d20a](fff0d20a79cdfa7044b95e38aba2cc7f58c39e8a)
* add acl solution and build pipeline [5dec70f2](5dec70f279c54063641dfc082c869757af9d6631)
* AvroSchemaBinding can serialise complex object [3f452772](3f45277223e300c2c513c889a9627dbed5ba2007)
* Simplify Conductor schema [52478376](5247837661d8615bd5b6c4f257211ec85b15bb84)
* Serialise simple data record [a73f3b06](a73f3b06e406619c7582130cf4249d96f389d24a)
* mongo failure logging [79ef7211](79ef721110a665ee75c1ffd48bf55a3870a67448)
* add bloomberg source [dba37ca9](dba37ca9bad00ea4ed7b102c801c15fe5407110c)
* keying component [1411b99a](1411b99a1543fccae3da162f070af45e77cd0198)
* add initial rimes ingest component [7a1d7c3a](7a1d7c3a4b13917ddffa97583283bb5951b9c94a)
* bloomberg test which works in isolation, but not with other tests (wip) [bac8a06b](bac8a06b2bfca1c1c3acb7634ae1b909f527b1e9)
* filter component [95f8fbcd](95f8fbcdfea537d35733deb45a93bf58ac96bc8a)
* add mongo sink component with integration test [d74b9971](d74b997128280c1b907ec9ece5e2d8467d8524d4)
* (wip) typing component to type data from input file [25c96612](25c96612a59a12048e85b5393af86321f036aac6)
* allow bloomberg file component to append data from heading metadata [aa913d2d](aa913d2d7f346fc1e189932373d5b61e8b9328ea)
* add roslyn analyser to enforce style rules [283e9fb8](283e9fb885c17a78d489403e5c68eb740e395413)
* basic deduplication component [5c96a369](5c96a369f7e60e9f070def983b3552748defb72d)

### Bug Fixes

* build via changes to project settings and gitlab-ci [23985a6e](23985a6e2ca122feb020c62c50a1b9bec9a84cfe)
* remove folder [040d81c0](040d81c07e8766f78197d2dedfdf094e7315f949)
* pulsar tests [9cf5d8b8](9cf5d8b843129a3240ec78c677a0f651aaeee9f6)
* deduplication component test [64730827](6473082772d6f2cf7e121a4cc287cde9a883f9b5)
* add error logging [80ebab9f](80ebab9ff8a47eed9cf8fb0b36e3e84a72508bf6)
* filename [7d6c7790](7d6c7790b2b0092db93fe057fb22f467e246ad1d)
* use ihs docker repo [33e5c3ac](33e5c3aca7e457b733092058e857a694ee0ab335)
* formatting [07b32bc3](07b32bc389b18cb564dc5f365d948f6b6172b23e)
* warnings [8ecc2737](8ecc273706feddfa79e880a442e6b726632aba38)
* temporarily stop using async method [4f7ce490](4f7ce490b8c31adeed3ad1b91f14d8be2d05035a)
* add missing awaits [b62d36e0](b62d36e0d5d67aed8782bb36c996b8c088b10bb9)
* formatting [551d28ab](551d28ab08689cc749015c23945b42ee334d9ed0)
* formatting [6736f64f](6736f64f48ebed0a012b17c01b1be550efaeb037)
* remove schema method from component [4d32b724](4d32b72418d8f935971a46df07c5097c1404e442)
* strict build errors [539875e4](539875e48eb6cee32f8295f315efba1dc0159e3a)
* strict build errors [6150270b](6150270bea82839239c25563ea0a2951b567e154)
* strict build errors [4cb5b30f](4cb5b30f8bebfca06ad99c35e4df5feeefef3966)
* format errors via cli [e0cefd55](e0cefd5549dce605485ec5ebf8c0316f3ad9984a)
* make test wait until pulsar is ready [cc44f6f8](cc44f6f883d123344bfdd2737e2c4c87855a6d99)

### Patches

* update packages highlighted by whitesource [eb3c2c8e](eb3c2c8e9db2b859e8d7ebbf4f72b920b0da78f1)
* add changelog generation [9864e1ab](9864e1ab7b9a15e0806e382287c290fb4be7432c)
* run stylcop analyzer across entire solution for ip compliance [d5c4ea1b](d5c4ea1b1da514c8cd87195fb623dad79d6bfe8c)
* Move application scoped tests out of Domain [137522f2](137522f22cff36da65762e350551d09041ffd3c6)
* add license file [558e5c00](558e5c00b2f0ff4a5f8f9fc9425a00dbf8a0e53b)
* Remove redundant project dependencies [32f3d124](32f3d124878a43365d5f28fab727e4e382983184)
* fix only:changes conditions which don't support variables [87c4579c](87c4579c04c8cf057236da051cb89729e98bf19f)
* suppress warnings [a990f664](a990f6641fa312d168effa55963e6f5a1c810b6c)
* fix formatting [b166cebb](b166cebbbfb8cfc366511a64bef669247aa4ec1e)
* suppress analyzer inspection of generated code [014dbc08](014dbc08da50a935f1a5672acd8462c5631c2baf)
* force pipeline to fail if there are build errors but the cli returns the wrong exit code [a4ebb26b](a4ebb26b52ff05680cb2d7233608651dbafb2641)
* gitlab ci file fix [2dd5886e](2dd5886e5f7e5e23a6125e5d85f708a8cf729155)
* Tidy up a few loose ends including fixing a saga bug, splitting aggregate events into separate stores [c9892f08](c9892f08d8c7d96409f45f5c7e8560d362471f5f)
* add acl sonarqube analysis [86021776](86021776d3721b6e00347abcf1f2e1f1d43f15da)
* sonarqube integration [b5d32765](b5d327659909a83ab911d6b3fe431340e0df9af6)
* update readme with test and versioning info [6de2f85f](6de2f85fb5a7a851a18b1887be0d60ed065cc2d5)
* allow intervention in semver calculation [518e17c1](518e17c17e73c074462095acd2269a6d9c5aef2a)
* Add run setting so integration tests can run lcoally [e016a013](e016a0137eeb030330b7fc72ece216e74ec64e75)
* add src folder [4857275e](4857275e953031fed496d60b562325883203ae68)
* move files [234d16f9](234d16f91885a9407b1b7e22d5845831c48db1bd)
* remove pointless arg from script [9be846fe](9be846fe3bc55f0c5e42fcaad49ee2292a338aa7)
* fix script [5d7739ba](5d7739baadfabd57f71c3a56d74bd3434d67dcc4)
* add version script and update ci [6ef89a4c](6ef89a4c7846745de2353b9891caa0e0d62c1132)
* add version script and update ci [21fb16e1](21fb16e16cf180ebb93ea04f85695611a709ebe7)
* Remove the Obsolete constraint for now [27d2733c](27d2733ca8c5f6648c51e47d945f6966957deedd)
* rename ISchemaMember to IPrimitiveSchema [00c8d179](00c8d179793a8e0822fbbfaf9684c7b2401f276d)
* fix pulsar config [23d30754](23d30754212ccb8157fcdde65d63f3fb5e8dce1c)
* formatting [2c1534b5](2c1534b5ef216e947666ee9db2916aadcabad2fe)
* add pulsar volume [be7097a1](be7097a1f81a830fc8ac1eec4c7129cb45d8cfc6)
* add source to bloomberg records correctly [ba29d98f](ba29d98fa4397a0586ca7a515591eb4fff480be2)
* add deduplicate component [e087b38d](e087b38dfc512325b8d614ad431881d05afb5c39)
* speculative fix [96d5adb4](96d5adb483e8e56031e1295ba60a4483b2eed23a)
* rename component to make its intent clearer [8e4fb59f](8e4fb59f2ac9f5a9afd1f5818246c192805af3c7)
* validation in bloomberg/rimes solution test [4bbc226a](4bbc226a0cdc1cc374647c69c50b6d56d360782f)
* rename component to clarify its purpose [94ce0bc6](94ce0bc61ecbceb8488cbc2d8bf22a9885e1aed7)
* Fix test [b8f6994c](b8f6994c04d98d26fdc4490c5916ffcd7966e574)
* wireup serilog to understand test failures [295d11a9](295d11a9e1e23352eb5b460a089bc6f10bfa8d4c)
* add more console output to diagnose issues in gitlab ci [73e77a60](73e77a6083fc313b5b4229c6ec3aef62a0f8a79e)
* add collection attribute to stop resource contention [c8a8d53c](c8a8d53cef5bde748d9686d110a0e9d44e54d0d9)
* working bloomberg and rimes solution (wipP [417e1a14](417e1a14d898ea49752a23ba8c5c3e4a1732c0da)
* up the assertion time [0a7bffc1](0a7bffc1d87dcd131633ee576ca732c758035f34)
* stop tests using same filename [21e20711](21e2071135dd683a083339ccb7370cd6d09b437c)
* speculative fix for mongo binding [cf5cb6ea](cf5cb6eacd4fdf1262da56b5696666e41d4c5b7a)
* file to class name [48d56ea7](48d56ea7ef4b0aa10b61711cbc2a01c6ebc3552e)
* fix connection string [c706f8b9](c706f8b9e5c396485b9455b53842ae1eb417f975)
* fix connection string [14956f5d](14956f5de54afd3df87062cc5c135610d4973961)
* speculative change to get integration tests running in pipeline [feb47246](feb47246dab25496c6568aa88ca7df8a3464bd5b)
* change test to use pulsar [7fc8d12d](7fc8d12d767ecd57ada6c6c8bf6423d07eed2f3b)
* add mongo sink solution [6241b57b](6241b57b44c90eea218b0384cd141c7534d95fd1)
* reduce duplicated LoC [37b9a56f](37b9a56f3e67a5228540b6ac6145ccc4eabf5464)
* add in-memory solution filter test [79864945](798649456d198fe8c5b613b8735333a217a844b9)
* resharper autofix to remove redundant code [135603a9](135603a90f1b86e8938eb015799e79d3fc396bd1)
* fixed initial bloomberg solution test [a1045e74](a1045e7404af233ddd00290809771ab94fef4f49)
* skip wip test [b9ff3488](b9ff348842e1880f5473350715547819fc50bab1)
* add logging to help understand the cause of test failures [e0578873](e0578873c0ea9020916363f3dfa7fb4c72fbcbc2)
* update readme with command for viewing warnings reliably locally [1e813d18](1e813d18b37869ecc797a275a7b22ac97fd86832)
* reorganise solution to accomodate more solution integration tests [744acc18](744acc18e49db0887c35d240bad0ce9dd1c56036)
* combine build and test to improve gitlab ci time [6432ce88](6432ce8890a45a7bddb2fcfe09e0d7636ce8b185)
* dotnet format instructions [1899fbeb](1899fbebcd98970779341ee27ade12db07731300)
* dotnet format autofixes [137c0660](137c066028745b2c566092fc89d7be14a9f96af4)
* improve clarity of readme [3a9226fe](3a9226feb180357e4b5adc04795d4a0c7c693427)
* add integration tests [039715e9](039715e996be33cc163cc5e93e183453ad549f79)
* Track record counts [884a468f](884a468f1fc4dbd7a7e716b882e042696c3a90a7)
* Further saga integration [7e3071f1](7e3071f17ef94a4581b2e53926394c8865a15233)
* Saga persistence [2fa0373f](2fa0373fab4ac6f87adc0534c22a6b681dfe9395)
* Improve log message [2d05e6d9](2d05e6d91c65abce3bdf3152cdf195c7617f67b1)

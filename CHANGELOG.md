# Changelog

[PyPI History][1]

[1]: https://pypi.org/project/google-cloud-asset/#history

### [3.7.1](https://www.github.com/googleapis/python-asset/compare/v3.7.0...v3.7.1) (2021-11-02)


### Bug Fixes

* **deps:** drop packaging dependency ([3f3e552](https://www.github.com/googleapis/python-asset/commit/3f3e5522e5e550e2f401238e8b7f3cfc31cd17e9))
* **deps:** require google-api-core >= 1.28.0 ([3f3e552](https://www.github.com/googleapis/python-asset/commit/3f3e5522e5e550e2f401238e8b7f3cfc31cd17e9))
* fix extras_require typo in setup.py ([3f3e552](https://www.github.com/googleapis/python-asset/commit/3f3e5522e5e550e2f401238e8b7f3cfc31cd17e9))


### Documentation

* list oneofs in docstring ([3f3e552](https://www.github.com/googleapis/python-asset/commit/3f3e5522e5e550e2f401238e8b7f3cfc31cd17e9))

## [3.7.0](https://www.github.com/googleapis/python-asset/compare/v3.6.1...v3.7.0) (2021-10-12)


### Features

* add context manager support in client ([#314](https://www.github.com/googleapis/python-asset/issues/314)) ([659db45](https://www.github.com/googleapis/python-asset/commit/659db456ff6cc7a09fffd83479b2b43d5905239f))

### [3.6.1](https://www.github.com/googleapis/python-asset/compare/v3.6.0...v3.6.1) (2021-09-30)


### Bug Fixes

* improper types in pagers generation ([fa08cbf](https://www.github.com/googleapis/python-asset/commit/fa08cbfbac5c8ce566883ad2c2e79ca5b4f32027))

## [3.6.0](https://www.github.com/googleapis/python-asset/compare/v3.5.0...v3.6.0) (2021-09-24)


### Bug Fixes

* add 'dict' annotation type to 'request' ([79a5a8a](https://www.github.com/googleapis/python-asset/commit/79a5a8a11d49c52162b9467e291df38f70634858))


### Documentation

* add relationship samples ([#293](https://www.github.com/googleapis/python-asset/issues/293)) ([473e133](https://www.github.com/googleapis/python-asset/commit/473e133e2674bf6a5ae655fe67be7d79fed2d8e9))

## [3.5.0](https://www.github.com/googleapis/python-asset/compare/v3.4.0...v3.5.0) (2021-09-03)


### Features

* add inventory_path ([#283](https://www.github.com/googleapis/python-asset/issues/283)) ([fbb47e6](https://www.github.com/googleapis/python-asset/commit/fbb47e6487fe454ca84d2415cf756a87bf66739f))
* **v1:** Add content type Relationship to support relationship search ([038febe](https://www.github.com/googleapis/python-asset/commit/038febe4c21d6ece23872e01cffc1110c59d6699))
* **v1:** add relationships ([#281](https://www.github.com/googleapis/python-asset/issues/281)) ([038febe](https://www.github.com/googleapis/python-asset/commit/038febe4c21d6ece23872e01cffc1110c59d6699))

## [3.4.0](https://www.github.com/googleapis/python-asset/compare/v3.3.0...v3.4.0) (2021-08-17)


### Features

* Release of relationships in v1, Add content type Relationship to support relationship export  ([#262](https://www.github.com/googleapis/python-asset/issues/262)) ([93c92c1](https://www.github.com/googleapis/python-asset/commit/93c92c150581d22ff2f7b63d7591b3a97191ff20))

## [3.3.0](https://www.github.com/googleapis/python-asset/compare/v3.2.1...v3.3.0) (2021-07-28)


### Features

* Add AnalyzeMove API ([a242adc](https://www.github.com/googleapis/python-asset/commit/a242adc8864724acb2d12136bb09d68cb7fc729c))
* Add AttachedResource field for ResourceSearchResult ([a242adc](https://www.github.com/googleapis/python-asset/commit/a242adc8864724acb2d12136bb09d68cb7fc729c))
* Add read_mask field for SearchAllResourcesRequest ([a242adc](https://www.github.com/googleapis/python-asset/commit/a242adc8864724acb2d12136bb09d68cb7fc729c))
* Add VersionedResource field for ResourceSearchResult ([a242adc](https://www.github.com/googleapis/python-asset/commit/a242adc8864724acb2d12136bb09d68cb7fc729c))
* Change metadata field for the AnalyzeIamPolicyLongrunning ([#245](https://www.github.com/googleapis/python-asset/issues/245)) ([a242adc](https://www.github.com/googleapis/python-asset/commit/a242adc8864724acb2d12136bb09d68cb7fc729c))


### Bug Fixes

* enable self signed jwt for grpc ([#244](https://www.github.com/googleapis/python-asset/issues/244)) ([a15e185](https://www.github.com/googleapis/python-asset/commit/a15e18574ce4d58a22955284ebfe444c152b30c7))


### Documentation

* add Samples section to CONTRIBUTING.rst ([#235](https://www.github.com/googleapis/python-asset/issues/235)) ([0d00e75](https://www.github.com/googleapis/python-asset/commit/0d00e75bf46d52beea0829b83a2df580a37491ca))


### [3.2.1](https://www.github.com/googleapis/python-asset/compare/v3.2.0...v3.2.1) (2021-07-21)


### Bug Fixes

* **deps:** pin 'google-{api,cloud}-core', 'google-auth' to allow 2.x versions ([#234](https://www.github.com/googleapis/python-asset/issues/234)) ([0687c84](https://www.github.com/googleapis/python-asset/commit/0687c843a2bca03ddd4671dfe2b40863dbba3fee))

## [3.2.0](https://www.github.com/googleapis/python-asset/compare/v3.1.0...v3.2.0) (2021-07-12)


### Features

* add always_use_jwt_access ([0a14f25](https://www.github.com/googleapis/python-asset/commit/0a14f25784a5d39b666709c2dc6521f014eea781))
* add new searchable fields (memberTypes, roles, project, folders and organization) in SearchAllIamPolicies ([0a14f25](https://www.github.com/googleapis/python-asset/commit/0a14f25784a5d39b666709c2dc6521f014eea781))
* new request fields (assetTypes and orderBy) in SearchAllIamPolicies ([0a14f25](https://www.github.com/googleapis/python-asset/commit/0a14f25784a5d39b666709c2dc6521f014eea781))
* new response fields (assetType, folders and organization) in SearchAllIamPolicies ([0a14f25](https://www.github.com/googleapis/python-asset/commit/0a14f25784a5d39b666709c2dc6521f014eea781))


### Bug Fixes

* disable always_use_jwt_access ([0a14f25](https://www.github.com/googleapis/python-asset/commit/0a14f25784a5d39b666709c2dc6521f014eea781))
* disable always_use_jwt_access ([#217](https://www.github.com/googleapis/python-asset/issues/217)) ([0a14f25](https://www.github.com/googleapis/python-asset/commit/0a14f25784a5d39b666709c2dc6521f014eea781))


### Documentation

* omit mention of Python 2.7 in 'CONTRIBUTING.rst' ([#1127](https://www.github.com/googleapis/python-asset/issues/1127)) ([#205](https://www.github.com/googleapis/python-asset/issues/205)) ([b9db51a](https://www.github.com/googleapis/python-asset/commit/b9db51a1e88615ab2da22da188d59987fcfca5d4)), closes [#1126](https://www.github.com/googleapis/python-asset/issues/1126)

## [3.1.0](https://www.github.com/googleapis/python-asset/compare/v3.0.0...v3.1.0) (2021-06-07)


### Features

* add `from_service_account_info` ([34278bf](https://www.github.com/googleapis/python-asset/commit/34278bf526384296e95196f755ab983c4efeca62))
* add Cloud Asset List API, add access time as condition context in request and evaluation value in response for Cloud Asset AnalyzeIamPolicy API, add more info (folders, organizations, kms_key, create_time, update_time, state, parent_full_resource_name, parent_asset_type) in response for Cloud Asset SearchAllResources API ([#196](https://www.github.com/googleapis/python-asset/issues/196)) ([69ecd23](https://www.github.com/googleapis/python-asset/commit/69ecd237ade97257c92ba8bbe6dd7a5eca83288f))
* support self-signed JWT flow for service accounts ([d0b9b21](https://www.github.com/googleapis/python-asset/commit/d0b9b21300eb9ad233cd8f7e0c73941bebc5fe46))


### Bug Fixes

* add async client to %name_%version/init.py ([d0b9b21](https://www.github.com/googleapis/python-asset/commit/d0b9b21300eb9ad233cd8f7e0c73941bebc5fe46))
* remove v1beta1 ([#127](https://www.github.com/googleapis/python-asset/issues/127)) ([dab2d53](https://www.github.com/googleapis/python-asset/commit/dab2d539a1c89c0a5f09df4c4cab4d86f1a4ab08))
* use correct retry deadlines ([#164](https://www.github.com/googleapis/python-asset/issues/164)) ([34278bf](https://www.github.com/googleapis/python-asset/commit/34278bf526384296e95196f755ab983c4efeca62))


### Documentation

* **python:** fix intersphinx link for google-auth ([#119](https://www.github.com/googleapis/python-asset/issues/119)) ([e455c9e](https://www.github.com/googleapis/python-asset/commit/e455c9e52641cd9f13440d342c9eeb931135889c))

## [2.2.0](https://www.github.com/googleapis/python-asset/compare/v2.1.0...v2.2.0) (2020-11-19)


### Features

* add AnalyzeIamPolicy and ExportIamPolicyAnalysis; support OSInventory; add common resource helper methods; expose client transport ([#113](https://www.github.com/googleapis/python-asset/issues/113)) ([3bf4c0a](https://www.github.com/googleapis/python-asset/commit/3bf4c0ab20346e3a12af168e20139f2cc067540a))


### Documentation

* remove note on editable installs ([#99](https://www.github.com/googleapis/python-asset/issues/99)) ([cf6072a](https://www.github.com/googleapis/python-asset/commit/cf6072a09b76dce78bd4c0c471c8c2d81186e0c6))

## [2.1.0](https://www.github.com/googleapis/python-asset/compare/v2.0.0...v2.1.0) (2020-09-25)


### Features

* add support for per type and partition export ([#86](https://www.github.com/googleapis/python-asset/issues/86)) ([cd26192](https://www.github.com/googleapis/python-asset/commit/cd2619262bbea00c01d054b783b218009171284e))


### Bug Fixes

* **sample:** mark a test with flaky ([#81](https://www.github.com/googleapis/python-asset/issues/81)) ([aa153dc](https://www.github.com/googleapis/python-asset/commit/aa153dce2f62c18101472c40964cc3cee9188d78)), closes [#75](https://www.github.com/googleapis/python-asset/issues/75)

## [2.0.0](https://www.github.com/googleapis/python-asset/compare/v1.3.0...v2.0.0) (2020-08-05)


### ⚠ BREAKING CHANGES

* move to microgenerator (#58)

### Features

* **asset:** Add sample code for two new RPCs. [([#4080](https://www.github.com/googleapis/python-asset/issues/4080))](https://github.com/GoogleCloudPlatform/python-docs-samples/issues/4080) ([3e935de](https://www.github.com/googleapis/python-asset/commit/3e935dea2db2f8528b5e5ba3f899bd9601037276))
* add sample code for ListAssets v1p5beta1 [([#4251](https://www.github.com/googleapis/python-asset/issues/4251))](https://github.com/GoogleCloudPlatform/python-docs-samples/issues/4251) ([187807f](https://www.github.com/googleapis/python-asset/commit/187807f07577f36daa88d5a2605c9eb1bf2918b7)), closes [#4250](https://www.github.com/googleapis/python-asset/issues/4250)
* move to microgenerator ([#58](https://www.github.com/googleapis/python-asset/issues/58)) ([3219b64](https://www.github.com/googleapis/python-asset/commit/3219b64c091d60ea62d669ee904517f73b07c0af))


### Bug Fixes

* limit asset types to avoid exceeding quota ([00b43e8](https://www.github.com/googleapis/python-asset/commit/00b43e8af859b85be16a0e59be32ac4844df77c4))

## [1.3.0](https://www.github.com/googleapis/python-asset/compare/v1.2.0...v1.3.0) (2020-06-25)


### Features

* generate v1p5beta1 ([#47](https://www.github.com/googleapis/python-asset/issues/47)) ([207eff4](https://www.github.com/googleapis/python-asset/commit/207eff44c20122c326bc939551f0177574d706dc))


### Bug Fixes

* update default retry configs ([#51](https://www.github.com/googleapis/python-asset/issues/51)) ([58f5d58](https://www.github.com/googleapis/python-asset/commit/58f5d58eba2f37af2a0161793fd61019a236cad3))

## [1.2.0](https://www.github.com/googleapis/python-asset/compare/v1.1.0...v1.2.0) (2020-06-23)


### Features

* **v1:** add support for condition in Feed ([#44](https://www.github.com/googleapis/python-asset/issues/44)) ([467ab58](https://www.github.com/googleapis/python-asset/commit/467ab58b43aa11d8d6f8087800e5d8b451984edc))

## [1.1.0](https://www.github.com/googleapis/python-asset/compare/v1.0.0...v1.1.0) (2020-06-10)

### Features

* add `search_all_resources` and `search_all_iam_policies` (via synth) ([#32](https://www.github.com/googleapis/python-asset/issues/32)) ([24a0827](https://www.github.com/googleapis/python-asset/commit/24a0827913dfa7563ea08cdf2e329626eadca4a3)), closes [#541](https://www.github.com/googleapis/python-asset/issues/541)

## [1.0.0](https://www.github.com/googleapis/python-asset/compare/v0.10.0...v1.0.0) (2020-06-10)


### Features

* release to GA ([#17](https://www.github.com/googleapis/python-asset/issues/17)) ([731e350](https://www.github.com/googleapis/python-asset/commit/731e350f6321a1b29b482ad360172754a2a255c6))

## [0.10.0](https://www.github.com/googleapis/python-asset/compare/v0.9.0...v0.10.0) (2020-05-08)


### Features

* add orgpolicy and accesscontextmanager (via synth) ([#26](https://www.github.com/googleapis/python-asset/issues/26)) ([c9d818e](https://www.github.com/googleapis/python-asset/commit/c9d818e4c53707d51395a33e6fc1b202126d6a29))

## [0.9.0](https://www.github.com/googleapis/python-asset/compare/v0.8.0...v0.9.0) (2020-03-17)


### Features

* add v1p4beta1 ([#16](https://www.github.com/googleapis/python-asset/issues/16)) ([b5771c3](https://www.github.com/googleapis/python-asset/commit/b5771c3bf6c580e414a998b63cef5400f2b3c50d))

## [0.8.0](https://www.github.com/googleapis/python-asset/compare/v0.7.0...v0.8.0) (2020-03-07)


### Features

* remove search resources and search iam policies support in v1p1beta1; remove export assets and batch get assets history from v1p2beta1 (via synth) ([#12](https://www.github.com/googleapis/python-asset/issues/12)) ([15b60a3](https://www.github.com/googleapis/python-asset/commit/15b60a349c93c928fe121dc47d44d812a0c14439))


### Bug Fixes

* **asset:** correct asset synthfile ([#10355](https://www.github.com/googleapis/python-asset/issues/10355)) ([32d9374](https://www.github.com/googleapis/python-asset/commit/32d937433109b55c8f6632d402859a38520ee153))

## 0.7.0

01-29-2020 10:53 PST

### New Features
- Add v1p1beta1, promote library to  beta. ([#10202](https://github.com/googleapis/google-cloud-python/pull/10202))
- Undeprecate resource name helper methods, add 2.7 deprecation warning (via synth).  ([#10036](https://github.com/googleapis/google-cloud-python/pull/10036))

## 0.6.0

12-12-2019 10:46 PST

### New Features
- Add real time feed support to v1 (via synth). ([#9930](https://github.com/googleapis/google-cloud-python/pull/9930))
- Deprecate resource name helper methods (via synth). ([#9827](https://github.com/googleapis/google-cloud-python/pull/9827))

### Documentation
- Change spacing in docs templates (via synth). ([#9736](https://github.com/googleapis/google-cloud-python/pull/9736))
- Add Python 2 sunset banner to documentation. ([#9036](https://github.com/googleapis/google-cloud-python/pull/9036))

### Internal / Testing Changes
- Normalize VPCSC configuration in systests. ([#9614](https://github.com/googleapis/google-cloud-python/pull/9614))

## 0.5.0

10-29-2019 14:26 PDT

### New Features
- Add `bigquery_destination` to `OutputConfig`; make `content_type` optional argument to `BatchGetAssetsHistoryRequest`; add `uri_prefix` to `GcsDestination`; add `ORG_POLICY` and `ACCESS_POLICY` content type enums ([#9555](https://github.com/googleapis/google-cloud-python/pull/9555))

### Documentation
- Remove compatability badges from READMEs. ([#9035](https://github.com/googleapis/google-cloud-python/pull/9035))

### Internal / Testing Changes
- Fix intersphinx reference to requests ([#9294](https://github.com/googleapis/google-cloud-python/pull/9294))
- Remove CI for gh-pages; use googleapis.dev for api_core refs ([#9085](https://github.com/googleapis/google-cloud-python/pull/9085))

## 0.4.1

08-12-2019 13:44 PDT

### Documentation
- Fix links to googleapis.dev ([#8998](https://github.com/googleapis/google-cloud-python/pull/8998))

## 0.4.0

08-01-2019 14:24 PDT

### New Features
- Generate asset v1p2beta1. ([#8888](https://github.com/googleapis/google-cloud-python/pull/8888))

### Internal / Testing Changes
- Update intersphinx mapping for requests. ([#8805](https://github.com/googleapis/google-cloud-python/pull/8805))

## 0.3.0

07-22-2019 17:42 PDT


### Implementation Changes
- Allow kwargs to be passed to create_channel (via synth). ([#8382](https://github.com/googleapis/google-cloud-python/pull/8382))
- Add nox session docs, add routing header to method metadata (via synth). ([#7919](https://github.com/googleapis/google-cloud-python/pull/7919))
- Remove classifier for Python 3.4 for end-of-life. ([#7535](https://github.com/googleapis/google-cloud-python/pull/7535))

### New Features
- Add 'client_options' support (via synth). ([#8498](https://github.com/googleapis/google-cloud-python/pull/8498))

### Dependencies
- Bump minimum version for google-api-core to 1.14.0. ([#8709](https://github.com/googleapis/google-cloud-python/pull/8709))
- Update pin for 'grpc-google-iam-v1' to 0.12.3+. ([#8647](https://github.com/googleapis/google-cloud-python/pull/8647))

### Documentation
- Link to googleapis.dev documentation in READMEs. ([#8705](https://github.com/googleapis/google-cloud-python/pull/8705))
- Add compatibility check badges to READMEs. ([#8288](https://github.com/googleapis/google-cloud-python/pull/8288))

### Internal / Testing Changes
- Update vpcsc test settings. ([#8627](https://github.com/googleapis/google-cloud-python/pull/8627))
- Pin black version (via synth) ([#8572](https://github.com/googleapis/google-cloud-python/pull/8572))
- Add VPCSC tests. ([#8613](https://github.com/googleapis/google-cloud-python/pull/8613))
- All: Add docs job to publish to googleapis.dev. ([#8464](https://github.com/googleapis/google-cloud-python/pull/8464))
- Add disclaimer to auto-generated template files (via synth). ([#8306](https://github.com/googleapis/google-cloud-python/pull/8306))
- Suppress checking 'cov-fail-under' in nox default session (via synth). ([#8232](https://github.com/googleapis/google-cloud-python/pull/8232))
- Fix coverage in 'types.py'. ([#8144](https://github.com/googleapis/google-cloud-python/pull/8144))
- Blacken noxfile.py, setup.py (via synth). ([#8114](https://github.com/googleapis/google-cloud-python/pull/8114))
-  Declare encoding as utf-8 in pb2 files (via synth). ([#8343](https://github.com/googleapis/google-cloud-python/pull/8343))
- Add empty lines (via synth). ([#8047](https://github.com/googleapis/google-cloud-python/pull/8047))

## 0.2.0

03-19-2019 12:17 PDT


### Implementation Changes
- Rename 'GcsDestination.uri' -> 'object_uri', docstring changes . ([#7202](https://github.com/googleapis/google-cloud-python/pull/7202))
- Protoc-generated serialization update.. ([#7073](https://github.com/googleapis/google-cloud-python/pull/7073))

### New Features
- Generate v1. ([#7513](https://github.com/googleapis/google-cloud-python/pull/7513))

### Documentation
- Fix broken links to Cloud Asset API ([#7524](https://github.com/googleapis/google-cloud-python/pull/7524))
- Updated client library documentation URLs. ([#7307](https://github.com/googleapis/google-cloud-python/pull/7307))
- Update copyright headers
- Pick up stub docstring fix in GAPIC generator.[#6963](https://github.com/googleapis/google-cloud-python/pull/6963))

### Internal / Testing Changes
- Add protos as an artifact to library ([#7205](https://github.com/googleapis/google-cloud-python/pull/7205))
- Add support for including protos in synth ([#7114](https://github.com/googleapis/google-cloud-python/pull/7114))

## 0.1.2

12-17-2018 16:15 PST


### Implementation Changes
- Use moved iam.policy now at google.api_core.iam.policy ([#6741](https://github.com/googleapis/google-cloud-python/pull/6741))
- Pick up enum fixes in the GAPIC generator. ([#6607](https://github.com/googleapis/google-cloud-python/pull/6607))
- Pick up fixes in GAPIC generator. ([#6489](https://github.com/googleapis/google-cloud-python/pull/6489))
- Fix client_info bug, update docstrings. ([#6403](https://github.com/googleapis/google-cloud-python/pull/6403))
- Synth docstring changes generated from updated protos ([#6349](https://github.com/googleapis/google-cloud-python/pull/6349))
- Generated cloud asset client files are under asset-[version] ([#6341](https://github.com/googleapis/google-cloud-python/pull/6341))

### New Features

### Dependencies
- Add 'mock' to unit test dependencies for autogen libs. ([#6402](https://github.com/googleapis/google-cloud-python/pull/6402))
- Bump minimum `api_core` version for all GAPIC libs to 1.4.1. ([#6391](https://github.com/googleapis/google-cloud-python/pull/6391))
- Avoid broken 'google-common-apis 1.5.4' release. ([#6355](https://github.com/googleapis/google-cloud-python/pull/6355))

### Documentation
- Document Python 2 deprecation ([#6910](https://github.com/googleapis/google-cloud-python/pull/6910))
- Fix docs build. ([#6351](https://github.com/googleapis/google-cloud-python/pull/6351))
- Normalize use of support level badges ([#6159](https://github.com/googleapis/google-cloud-python/pull/6159))

### Internal / Testing Changes
- Add templating to asset synth.py ([#6606](https://github.com/googleapis/google-cloud-python/pull/6606))
- Add synth metadata. ([#6560](https://github.com/googleapis/google-cloud-python/pull/6560))
- Update noxfile.
- Blacken all gen'd libs ([#6792](https://github.com/googleapis/google-cloud-python/pull/6792))
- Omit local deps ([#6701](https://github.com/googleapis/google-cloud-python/pull/6701))
- Run black at end of synth.py ([#6698](https://github.com/googleapis/google-cloud-python/pull/6698))
- Unblack gapic and protos.
- Run Black on Generated libraries ([#6666](https://github.com/googleapis/google-cloud-python/pull/6666))
- Add templates for flake8, coveragerc, noxfile, and black. ([#6642](https://github.com/googleapis/google-cloud-python/pull/6642))
- Add / fix badges for PyPI / versions. ([#6158](https://github.com/googleapis/google-cloud-python/pull/6158))
- Use new Nox ([#6175](https://github.com/googleapis/google-cloud-python/pull/6175))

## 0.1.1

### Packaging
- Release as `google-cloud-asset`, rather than `google-cloud-cloudasset` ([#5998](https://github.com/googleapis/google-cloud-python/pull/5998))

## 0.1.0

Initial release.

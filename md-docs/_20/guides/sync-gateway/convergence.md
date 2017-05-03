---
title: Convergence
permalink: guides/sync-gateway/index.html
---

Plan:

- [ ] Update configuration file [reference](https://developer.couchbase.com/documentation/mobile/current/guides/sync-gateway/config-properties/index.html) (Adam)
	- The backing yaml file must be updated here on the [convergence](https://github.com/couchbaselabs/couchbase-mobile-portal/blob/convergence/configs/20/sg.yaml) branch.
- [ ] Provide example config for most common scenario (Adam)
	- Can be inserted on the stub [convergence.md](https://github.com/couchbaselabs/couchbase-mobile-portal/blob/convergence/md-docs/_20/guides/sync-gateway/convergence.md) file.
- [ ] Conceptual explanation of a server-only application that starts using mobile
	- Provide what is expected from an end user point of view (Sachin)
		1. Pre-deployment planning
			- User creation for mobile users – why? How are these different from server users?
			- Choose an authentication option from the ones available – link to the different portions of the SG guide
			- Choose which documents/buckets would be enabled for convergence (auto-import)
		2. Deployment
			- Create a SG cluster
			- Configuration of SG
			- Configure docs/buckets for mobile enablement/auto-import
		3. Add CBL to mobile application
			- Link to getting started guides on dev portal
	- Provide implementation notes and details (Adam)
- [ ] Conceptual explanation of a mobile-only application that starts using server SDKs.
	- Provide what is expected from an end user point of view (Sachin)
		1. Pre-deployment planning
			- Choose the application development strategy for the server application developed using one of our SDKs.
			- Choose which documents/buckets would be enabled for convergence (auto-import)
		2. Deployment
			- Upgrade CB server cluster to Spock and SG to 2.1
			- Configuration of SG
			- Configure docs/buckets for mobile enablement/auto-import
		3. Impact on mobile app
			- No impact. Call out the compatibility between SG 2.x and CBL 1.x
	- Provide implementation notes and details (Adam)
- [ ] Release notes for convergence.
	- Improve the process to edit/review release notes. Scope already covered in [#596](https://github.com/couchbaselabs/couchbase-mobile-portal/issues/596) (James)
	Edit the release notes once the process is improved (Adam)

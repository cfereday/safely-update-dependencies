# safely-update-dependencies
A script to safely keep up to date with dependencies

## Idea:
* Use npm audit & npm update together 
* Only update dependencies to a safe version. If a version has a vulnerability, suggest the patched version to update to.
* Have a CLI output to see your dependencies & the next safest version they could be bumped to
* Option to update dependencies to next safest version for all: bump, minor & major 
* Options to specify which semver versions of dependencies to update, i.e, update bump / minor / major 
* If you choose to update the major version, CLI warns you to check for breaking changes. Provides you with the URL to the changelog of that dependency repo. 

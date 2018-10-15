# Project Charter

Links to project pages:
* https://github.com/voxpupuli/puppet-puppetwebhook
* https://github.com/voxpupuli/puppet_webhook


## Mission
Create easy ways for end users to install, setup and utilize Vox Pupuli's Webhook API server for Puppet within their environment.

This includes, but may not be limited to:

1. Creating Deb and RPM packages for easy installation.
2. Hosting those packages in publicly available APT and YUM repositories.
3. Creating an easy way to manage the installation and integration of the Puppet Webhook API Server via Puppet.

## End User Benefit
Simplify the process of getting the puppet_webhook API server up and running.

## Vision
Puppet has made great strides in automating workflows, infrastructure, deployments and more for end users, but there still exist some areas where the tool is limited. Most notable being the automated deployment of modules, roles, profiles, and hieradata automatically via a REST call or Git webhook in the Puppet Open Source tool.

## Success Criteria
* Version 1.0.0 of puppetwebhook module must be released on the Forge under the puppet namespace.
* Deb and RPM packages built for the puppet_webhook API server itself.
* Public APT and YUM repositories for installing the API server.
* [Optional] Arch packages

## Constraints
* Limited funding for Vox Pupuli to host APT/YUM Repositories
* Consensus on default configuration for Deb/RPM packages
  * Do we require `puppet-agent`, system packages, or support both?

## Assumptions
None, beyond the obvious.

## Team Members
Vox Pupuli Collaborators
Vox Pupuli PMC
Puppet Users

# kong-summit-2020

Sharing Kongness with the world

## Repository structure


## Access needed

Create an RBAC user for each workspace, this example is tested with RBAC users 
with superadmin workspace permissions.

In this repository we are managing:

- APIs definitions of:
    - first-workspace
    - second-workspace
    - third-workspace
- Developer portal settings of:
    - first-workspace
    - second-workspace
    - third-workspace

    
Change tokens and urls on all the config files, these files should be git-crypted or added as a secret during
CI/CD process:

* `portal/workspaces/<workspace>/cli.conf.yaml`
* `deck/<workspace>/deck.yaml`
# Contexts/Workspaces on CircleCi
Circle Ci is a continuos deployment tool that help to test, build and deploy applications
easier and quicker on multiple platforms.

## config.yml
For setting up a project with CircleCi is neccesary to create a configuration file: `config.yml` in the `.circleci` folder.

## Version
Circle Ci version

## Jobs
## ******************************
Independent environment that can execute steps or commands, like:
- _Install_
- _Execute_
- _Build_
- _Store cache_
- _Restore cache_

## Docker image
Docker image used to create the container environment
*_CircleCi has prebuilt images_

## Working directory
Current directory where the steps will run

## Steps
Commands that will be executed

## Checkout
Checkout the code from current branch

## Run
Execute a bash command

## Save_cache
Store a dir or a file in the CircleCi storage

## Restore_cache
Restore cache with a cache key

## Workflows
## ******************************
Set the flow configuration to excecute the jobs, a job can be executed always or in a specific branch or tag also can can be executed sequentially or in parallel

## Contexts
## ******************************
Are a mechanism for securing and sharing environment variables across projects

## Workspace
## ******************************
The workflow has an associated workspace which can be used to transfer files (_persist_to_workspace_/__) between jobs


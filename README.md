# Planck's Cloud Installer #

<a href="https://plancks.cloud/"><img src="https://plancks.cloud/img/icon.svg" width="150"></a>

## System requirements ##
- 64mb Ram Requirements
- 10mb HDD Requirements

## Software Requirements ##

- Docker
- Google gVisor (on Linux only)

## Setup ##

- Open command prompt (Windows) or terminal (Unix / Linux)
- Run `docker swarm init`
- Run `docker service create -d --name brutus planckscloud/brutus:latest`
- Wait a few minutes (depending on your Internet connection).
- Open your browser to http://localhost:6108. 

## Advanced ##

- Setup for more than one machine.
- Ingress for hosting sites.

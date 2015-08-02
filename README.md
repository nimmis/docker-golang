
lang Dockerfile
===============
[![Docker Hub; nimmis/golang](https://img.shields.io/badge/dockerhub-nimmis%2Fgolang-green.svg)](https://registry.hub.docker.com/u/nimmis/golang)

Docker container with GO programming language with different versions ontop of Ubuntu 14.04

Based on [![Docker Hub; nimmis/ubuntu](https://img.shields.io/badge/dockerhub-nimmis%2Fubuntu-green.svg)](https://registry.hub.docker.com/u/nimmis/ubuntu) with working init process and syslog. For more information on how to set upp services, please read the dockumentation for [nimmis/ubuntu](https://registry.hub.docker.com/u/nimmis/ubuntu)

### Installation

This continer should normaly run as a daemon i.e with the -d flag attached

    docker run -d nimmis/golang

Accessing the container with a bash shell can be done with

	docker exec -ti <container ID> /bin/bash

### TAGs

This image only contains the 2 latest LTS versions of Ubuntu 12.04 and 14.04, the versions are
nimmis/ubuntu:<tag> where tag is

- latest -  this gives the latest version (atm 1.4.2)
- 1.4.1  -  this gives the 1.4.1 version
- 1.4.2  -  this giver the 1.4.2 version
- 1.4    -  this gives the 1.4 version
- 1.3.3  -  this gives the 1.3.3 version
- 1.3    -  this giver the 1.3 version
- 1.2.2  -  this gives the 1.2.2 version


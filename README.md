
lang Dockerfile
===============
[![](https://images.microbadger.com/badges/image/nimmis/golang.svg)](https://microbadger.com/images/nimmis/golang "Get your own image badge on microbadger.com")

Docker container with GO programming language with different versions ontop of Ubuntu 14.04

Based on [![Docker Hub; nimmis/ubuntu](https://img.shields.io/badge/dockerhub-nimmis%2Fubuntu-green.svg)](https://registry.hub.docker.com/u/nimmis/ubuntu) with working init process and syslog. For more information on how to set upp services, please read the dockumentation for [nimmis/ubuntu](https://registry.hub.docker.com/u/nimmis/ubuntu)

### Installation

This continer should normaly run as a daemon i.e with the -d flag attached

    docker run -d nimmis/golang

Accessing the container with a bash shell can be done with

	docker exec -ti <container ID> /bin/bash

### TAGs

This image contains version 1.2.2 to the latest version (atm 1.7.3), the versions are nimmis/golang:<tag> where tag is

| Tag    | Alpine version | size |
| ------ | -------------- | ---- |
| latest |  this gives the latest version (atm 1.8.1) | [![](https://images.microbadger.com/badges/image/nimmis/golang.svg)](https://microbadger.com/images/nimmis/golang "Get your own image badge on microbadger.com") |
| 1.8.1  |  this is the 1.8.1 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.8.1.svg)](https://microbadger.com/images/nimmis/golang:1.8.1 "Get your own image badge on microbadger.com") |
| 1.8  |  this is the 1.8 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.8.svg)](https://microbadger.com/images/nimmis/golang:1.8 "Get your own image badge on microbadger.com") |
| 1.7.5  |  this is the 1.7.5 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.7.5.svg)](https://microbadger.com/images/nimmis/golang:1.7.5 "Get your own image badge on microbadger.com") |
| 1.7.3  |  this is the 1.7.3 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.7.3.svg)](https://microbadger.com/images/nimmis/golang:1.7.3 "Get your own image badge on microbadger.com") |
| 1.7.1  |  this is the 1.7.1 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.7.1.svg)](https://microbadger.com/images/nimmis/golang:1.7.1 "Get your own image badge on microbadger.com") |
| 1.7    |  this is the 1.7 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.7.svg)](https://microbadger.com/images/nimmis/golang:1.7 "Get your own image badge on microbadger.com")|
| 1.6.3  |  this is the 1.6.3 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.6.3.svg)](https://microbadger.com/images/nimmis/golang:1.6.3 "Get your own image badge on microbadger.com")|
| 1.6.2  |  this is the 1.6.2 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.6.2.svg)](https://microbadger.com/images/nimmis/golang:1.6.2 "Get your own image badge on microbadger.com")|
| 1.6    |  this is the 1.6 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.6.svg)](https://microbadger.com/images/nimmis/golang:1.6 "Get your own image badge on microbadger.com") |
| 1.5.3  |  this is the 1.5.3 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.5.3.svg)](https://microbadger.com/images/nimmis/golang:1.5.3 "Get your own image badge on microbadger.com") |
| 1.5    |  this is the 1.5 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.5.svg)](https://microbadger.com/images/nimmis/golang:1.5 "Get your own image badge on microbadger.com") |
| 1.4.2  |  this is the the 1.4.2 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.4.2.svg)](https://microbadger.com/images/nimmis/golang:1.4.2 "Get your own image badge on microbadger.com") |
| 1.4.1  |  this is the the 1.4.1 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.4.1.svg)](https://microbadger.com/images/nimmis/golang:1.4.1 "Get your own image badge on microbadger.com") |
| 1.4    |  this is the the 1.4 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.4.svg)](https://microbadger.com/images/nimmis/golang:1.4 "Get your own image badge on microbadger.com") |
| 1.3.3  |  this is the the 1.3.3 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.3.3.svg)](https://microbadger.com/images/nimmis/golang:1.3.3 "Get your own image badge on microbadger.com") |
| 1.3    |  this is the the 1.3 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.3.svg)](https://microbadger.com/images/nimmis/golang:1.3 "Get your own image badge on microbadger.com") |
| 1.2.2  |  this is the the 1.2.2 version | [![](https://images.microbadger.com/badges/image/nimmis/golang:1.2.2.svg)](https://microbadger.com/images/nimmis/golang:1.2.2 "Get your own image badge on microbadger.com") |


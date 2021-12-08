From nimmis/ubuntu

MAINTAINER nimmis <kjell.havneskold@gmail.com>

ENV GO_VERSION=1.13.15 \
    GOROOT=/goroot \
    GOPATH=/gopath 

ENV PATH $PATH:$GOROOT/bin:$GOPATH/bin

RUN apt-get update -y && \

    # Install needed packages
    apt-get install --no-install-recommends -y -q curl build-essential ca-certificates git mercurial bzr && \

    # Install go
    mkdir /goroot && curl https://storage.googleapis.com/golang/go${GO_VERSION}.linux-amd64.tar.gz | tar xvzf - -C /goroot --strip-components=1 && \
    mkdir /gopath && \

    # remove apt cache from image
    apt-get clean all


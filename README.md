# HAProxy 1.7 for arm64

Docker image to run haproxy 1.7 on my Pine64, based on [this](https://hub.docker.com/r/project31/aarch64-centos/) CentOS 7 for arm64 image. 

## HAProxy version

`1.7.4`

## Base image

`project31/aarch64-centos`

## Build and run the container
Before building the image, ensure that you have the `haproxy.tar.gz` and your `haproxy.cfg` file in the same directory as the Dockerfile. 
To download `haproxy.tar.gz` run the command: 
```
wget -O haproxy.tar.gz "http://haproxy.1wt.eu/download/1.7/src/haproxy-1.7.4.tar.gz"
```
Then build and run your docker container as usual. 

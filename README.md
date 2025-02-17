# docker-images

Some docker images with common dev tools for saving time.

## cityuderek/ubuntu

For general use, such as debug

Main features: node, npm, git, mysql

Tools: curl, wget, ping, ifconfig, zip

To run:

```
docker run -it --rm -v .:/app -w /app cityuderek/node-ubuntu sh
```

https://hub.docker.com/r/cityuderek/ubuntu

## cityuderek/node-alpine

For general use, such as debug

Main features: node, npm, git, mysql

Tools: curl, wget, ping, ifconfig

To run:

```
docker run -it --rm -v .:/app -w /app cityuderek/node-alpine sh
```

https://hub.docker.com/r/cityuderek/node-alpine

## cityuderek/docker-aws-py3

Light weight image for deployment.

Included: awscli

Tools: wget, ping, ifconfig

To run:

```
docker run -it --rm -v .:/app -w /app cityuderek/docker-aws-py3 sh
```

https://hub.docker.com/r/cityuderek/docker-aws-py3

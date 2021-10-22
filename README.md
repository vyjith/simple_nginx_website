# Nginx website contiersation (Docker)
[![Builds](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
-------------------------------------------------- 

# Description

Creating a nginx website with the help of Dockerfile 

-------------------------------------------------- 

# Feature

- A simple Docker file for image creation
- Usage of Alpine OS as bas image to reduce the size of image that built.

-------------------------------------------------- 

# Prerequisites

-------------------------------------------------- 
- Need to have Docker installed in your machine
- Need to have Git insalled in your machine

# Insallation

- [Dccker installation](https://docs.docker.com/engine/install/ubuntu/)
- Alternatively from the above, you can use pre-installed [Docker Teaminal]((https://labs.play-with-docker.com/) (For the easy access to configured Docker environment especially for begineers)
- [Git insallation](https://git-scm.com/download/linux)

-------------------------------------------------- 

# How to build an image with Dockerfile
_Steps:_
```sh 
yum insall docker -y
systemctl start docker
yum insall git -y
git clone https://github.com/vyjith/simple_nginx_website
cd simple_nginx_website
docker build -t <your_name_image:tag> .
#eg: docker build -t nginx_app:10 .
docker image ls <-------------------------------------------------- image will list here 


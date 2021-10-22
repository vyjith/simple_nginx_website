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
#eg: docker build -t simple_nginx:10 .
docker image ls <-------------------------------------------------- image will list here 
docker run --rm -d -p 8080:80 simple_nginx:10  <-------------------------------------------------- Here we are running the image on port 8080
command line exaplation of docker run command
--rm                             Automatically remove the container when it exits
-p, --publish list                   Publish a container's port(s) to the host
-d, --detach                         Run container in background and print container ID
```
-------------------------------------------------- 

Please find the below screenshot of the Docker building an image.


![alt text](https://i.ibb.co/nMTksmQ/image.png)

-------------------------------------------------- 
You can see that the below docker images (docker image ls)
![alt text](https://i.ibb.co/s9x62VH/image.png)




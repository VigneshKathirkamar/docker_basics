# docker_basics
## Basics of Docker
### Step : 1
Install docker on you ubuntu system using the following command
``` 
sudo apt update
sudo apt install docker.io
```
### Step : 2
Check the version of the docker 
```
docker -v 
```
### Step : 3
Let's run our first container (an ubuntu container) with ubuntu latest image from the docker hub.
Containers are a type of virtualisation technique where you can put your application with it's dependencies and configuration together
```
sudo docker run --name MyUbuntu ubuntu:latest
```
the above command pulls ubuntu container from docker hub and runs the container

use ``` sudo docker ps -a ``` will list down some details about the containers

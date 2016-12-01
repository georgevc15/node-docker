## Synopsis
Build a node image with a simple node express server that can be runned inside a container 


## Installation
1) Have docker installed on your machine
2) Run docker-machine env default
3) Run the env command received on step 2
4) docker build -f Dockerfile -tag yourduckerhubusername/node .
5) docker run -d -p 8080:3000 yourduckerhubusername/node
5) Test it http://192.168.99.100:8080/

--- Remove the image an the container
a) docker stop [container id] //stop container
b) docker rm [container id] //delete container
c) docker rmi [image id] //delete image







# Javascript OOP Product App

This is a simple Vanilla Javascript Frontend CRUD that uses Object Orientend Programming using Ecmascript 6+ Features.

![](docs/screenshot.png)

# Requirements
- Docker must be installed on your local machine.
- command to install Docker as per your linux distribution
```
$ sudo yum install docker -y
        or
$ sudo apt-get install docker.io -y
```
- You do not need a Java JDK

# Steps to Run app using Docker
Step -1 : Check Docker is insalled or not on a system, if not then Install docker in system using above commands
```
$ docker --version
```

Step -2 : Git clone the code to local system using 'git clone'

Step -3 : Build Docker image from Dockerfile and check for image by using following command
```
$ sudo  docker build . -t my_javascript_img:latest
$ sudo docker images
```
![image](https://user-images.githubusercontent.com/117855172/224004024-51823f63-fe24-4db2-a9ba-36a065a443ee.png)

step -4 : Run the docker image by 
```
$ docker run -d -p 8080:8080 my_javascript_img:latest
```
        This will run container in background 
check container status by 
```
$ sudo docker ps
```
![image](https://user-images.githubusercontent.com/117855172/224004801-16b4571b-415c-43b6-87c3-d21c9b75e126.png)


now for local machine visit http://localhost:8080
or for VM over cloud visit "http://<public_ip_of_system>:8080"
# Project Structure

- `src` is the folder with the source code

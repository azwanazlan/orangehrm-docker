# orangehrm-docker

- Hi, this is docker-compose.yml for old version of orangehrm (v4.10) source folder that I fixed from other sources. 

- This will allow old version of orangehrm to be installed in your machine with Docker.

- The purpose of using Docker is to allow orangehrm to be installed its own container (with php 7.4 + mariadb 10.6)

- Useful if you have many project sources inside your machine which have latest version of php and mariadb/mysql which the old version of orangehrm cannot be installed    with.

- As you know orangehrm is a good web application and has many complex features to be explored by QA automation tester to test their skill of using automation tools

## How to install (easy installation)

1. Install Docker for Desktop
2. Install portainer.io (container management application) extension for Docker
3. Navigate to portainer extension and go to stacks tab ---> add new stack ---> name it as orangehrm ---> copy docker-compose.yml content and paste it into web editor ---> click deploy the stack and wait for a moment for the Docker to build the container
4. Now there are new orangehrm container exists in your docker. Go to localhost:8181 and proceed to the installation of orangehrm

![App Screenshot](https://github.com/azwanazlan/orangehrm-docker/blob/master/Screenshot%202022-09-21%20175802.png)

for details on how to install: https://www.youtube.com/watch?v=5MbhrApqU-Y&t=225s



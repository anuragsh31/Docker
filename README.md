# Docker

## Task-1

``` docker -v ```

Command is used to get the currently installed version of docker


![01](https://user-images.githubusercontent.com/106172048/194724595-c0fbac54-b623-45cd-b5b4-10efd2be70d9.jpg)


``` docker pull docker/getting-started```

Command is used to pull images from the docker repository

![02](https://user-images.githubusercontent.com/106172048/194724599-4df874c5-0cc9-49e5-8f93-b5342a14e7fc.jpg)


``` docker images```

Command is used to list all the docker images available locally in your system.

![03](https://user-images.githubusercontent.com/106172048/194724608-d02c8a05-653b-4030-a6d4-20223a8f1439.jpg)


```docker run -d -p 80:80 docker/getting-started```

Command is used to run the docker image

![04](https://user-images.githubusercontent.com/106172048/194724611-7d9b19a4-da70-459d-adfb-36090231b6c9.jpg)


```docker ps```

Command is used to list the running containers

![05](https://user-images.githubusercontent.com/106172048/194724613-281367c9-8e89-4d29-a3c7-dc788484eaf5.jpg)


```docker ps -a```

Command is used to show all the running and exited containers


![](Docker_command/14_allContainer.jpg)



```docker rename fd311ab86780 web```

Command is used to rename the containers

![](Docker_command/13_rename.jpg)

```docker rm thirsty_jones```

Command is used to delete the containers

![](Docker_command/15_deleteContainer.jpg)

``` docker stop de5b3104321c```

This command stops a running container

![07](https://user-images.githubusercontent.com/106172048/194724617-06669763-2f6a-4b2d-a9f9-7e95ddb09f8e.jpg)

```docker exec -it fd311ab86780 bash```
This command is used to access the running container

![](Docker_command/16.jpg)


```docker image rm -f cb90f98fd791```

Command is used to remove the image

![06](https://user-images.githubusercontent.com/106172048/194724615-2549aca0-fabc-42c6-807f-90343b5d4e63.jpg)

```docker rmi -f hello-world```
Command is used to remove the image by using given image name

![](Docker_command/08.jpg)


```docker build -t anuragsh31/helloapp .```

Command is used to build docker image in repository

![](Docker_command/11_buildRepository.jpg)



```docker push anuragsh31/helloapp:latest ```

This command is used to push an image to the docker hub repository

![](Docker_command/12_Push.jpg)


```docker system df```


Command is used to show docker disk usage

![](Docker_command/17_dockersystem.jpg)


## Task-2:



![](Docker_command/2.jpg)


## Task-3:

[Hello_world_application](https://github.com/anuragsh31/Docker/tree/master/Hello_World_Application)


## Task -4

[Application](https://github.com/anuragsh31/Docker/tree/master/App)

[DockerHub](https://hub.docker.com/r/anuragsh31/newapp)



![](Docker_command/task-3_1.jpg)

![](Docker_command/task-3_2.jpg)

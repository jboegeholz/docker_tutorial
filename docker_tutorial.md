# Docker Tutorial

A Container is a running instance of an Image



## Docker CLI commands

| Command  | Meaning   | 
|---|---|
| docker pull <image_name>  | download an iamge from dockerhub  | 
| docker images  | show list of locally available docker iamges  |
| docker start <container_id>   | start container  |
| docker stop <container_id>   | stop container  |
| docker run <image_name>    | pulls image, make a container from image and runs it  |
| docker run -d <image_name>    | running in detached mode  |
| docker run -p<host_port>:<container_port> <image_name>    | port binding e.g. -p6000:6379  |
| docker ps   | show a list of running containers  |
| docker ps -a  | show a list of running **and stopped** containers  |
| docker logs <container_id>  | gets the log from the running container |
| docker exec -it <container_id> /bin/bash | interactive terminal |
| ocker rename <container_name> <new_container_name> | rename a container |



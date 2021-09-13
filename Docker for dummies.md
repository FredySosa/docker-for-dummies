# Docker for dummies

* to run a docker image
**docker run \<options\> (\-\-help to get help) \<docker image\>**
_docker run hello-world_


* to run a docker image and a command
**docker run \<docker image\> \<command\>**
_docker run busybox echo hello world_


* docker run = docker create + docker start
_docker run hello-world_
=
_docker create hello-world
docker start \<options\> \<container-id\>_


* to list docker containers
**docker ps \<options\> (\-\-help to get help)**


* to get the logs of a container
 **docker logs \<container-id\>**


* to stop a container (waiting 10 seconds)
**docker stop \<container-id\>** 


* to stop inmediately a container
**docker kill \<container-id\>**


* to delete all stopped containers
**docker system prune**


* to execute a command in a docker container
**docker exec -it \<container-id\> \<command-to-run\>**


* to execute shell. most common shell programm: sh
**docker exec -it \<sh|bash\>**



# Docker

Stop all running containers:

$ docker stop $(docker ps -q)
$ docker container stop $(docker container ls -q)

Remove all stopped containers:

$ docker container prune
$ docker rmi $(docker images -a -q)

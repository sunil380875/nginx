install docker desktop and cli

# Run a image

docker run -it image-name
eg: docker run -it ubuntu //-it mean iter-active

# Basic commands

docker container ls // List all running container
docker container ls -a // List all container (start + stop)

# start a stop container

docker start containerId/name
docker stop containerId/name

# Run a command without going inside container

docker exec containerId -ls || any os command

# Going inside container

docker exec -it containerId bash

# Port mapping and expose to local

docker run -it -p 1000:1000 image-name
1000:1000
local container


Delete All Previous container
docker container prune -f

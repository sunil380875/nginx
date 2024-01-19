install docker desktop and cli

# Run a image

docker run -it image-name
eg: docker run -it ubuntu //-it mean iter-active

# Basic commands

docker container -ls // List all running container
docker container -la -a // List all container (start + stop)

# start a stop container

docker start containerId/name
docker stop containerId/name

# Run a command without going inside container

docker exec containerId -ls || any os command

# Going inside container

docker exec -it containerId bash

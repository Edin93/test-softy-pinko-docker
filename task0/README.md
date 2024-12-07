##### image building command
* `docker build -f ./Dockerfile -t softy-pinko:task0 .`

##### container launching command
* `docker run -it --rm --name softy-pinko-task0 softy-pinko:task0`

##### Command to delete all the containers, including its volumes
* `docker rm -vf $(docker ps -aq)`

##### Command to delete all the images
* `docker rmi -f $(docker images -aq)`

myphpapp.app
-------------
In this example, I will be setting up Named Volumes in Docker to share data between different docker containers.

Terminal commands:
#this creates a volumn with a specific name. If no name is set, it will use whatever is set in the docker-compose.yml
#file to identify name convention
    docker volume create --name my-vol 


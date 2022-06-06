# docker

docker stop :to stop container

how to check running containers: docker ps

download image:docker pull <image-name>
  
  
docker run image: docker run -it/d <imagename> -p 7080<host machine>:8080<local machine> --name=any-name
  
docker exec -it <container_id> /bin/bash :to login to container

  
  docker images to check all images
  docker rmi <image name> --> to delete image
  
  docker rm <containername/id> --> to remove cobtainer
  docker stop/start/restart containername/id --> to stop or start or restart
  docker stats container id -->usage
  docker kill conta id
  
  docker inspect imageid -->configuration
  
  non-root user docker ps -a
  
  docker history imageid
  
  

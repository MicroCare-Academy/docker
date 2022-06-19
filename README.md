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
  
  ENTRYPOINT
WORKDIR
ENV
CMD
COPY



docker run -d jenkins/jenkins -v /home/demo:/Users/sh030348/sonar -p 7082:8080

sudo docker run –d –volume-driver=flocker –v /home/demo:/var/jenkins_home –p  8080:8080 –p 50000:50000 jenkins/jenkins


sudo docker volume create –-name=demo –opt o=size=100m

sudo docker volume ls

docker network ls

sudo docker network  inspect bridge

sudo docker network create –-driver bridge new_nw

sudo docker run –it –network=new_nw ubuntu:latest /bin/bash
sudo docker network inspect new_nw

docker build -t syed0071/getting-started:1.0 .
  
  https://github.com/docker/getting-started
  
  
  

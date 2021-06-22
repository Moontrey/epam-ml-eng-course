docker exec -it d35ef5a5917f bash

docker cp wine.data d35ef5a5917f:/home/jovyan/wine.data

docker run -v /home/moontrey/Documents/docker:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:17aba6048f44

docker build -t test_docker .
docker run -v /home/moontrey/Documents/docker:/home/jovyan/ -p 8888:8888 test_docker

building with arguments
docker-compose build --build-arg GROUP_ID="23423432423"
and after
docker-compose up
for starspace
sudo apt-get install build-essential g++

TO CHECK IMAGES EXISTING
docker images

delete all IMAGES
docker rmi imake id

TO CHECK CONTAINERS EXISTING
docker ps -a

delete all containers
docker rm $(docker ps -aq)

TO RUN EXISTING CONTAINER
docker run -it "id_container"

GET INTO CONTAINER 
docker exec -it "id_container" bash

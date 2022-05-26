# Docker


docker run nginx>>>>>used to display images


docker ps>>> used to list the containers

docker ps -a>>>

docker stop>>
docker stop silly_sammet

docker rm>>> to remove docker permanently

docker images>> to shoe all images


STOP – stop a container

docker rmi nginx>>t remove ngnix image

docker pull nginx > download an image

Append a command
docker run ubuntu>>
docker run ubuntu sleep 5

Run – attach and detach
docker run kodekloud/simple-webapp
docker run –d kodekloud/simple-webapp
docker attach a043d


Run – tag
docker run redis
docker run redis:4.0 

RUN - STDIN
docker run kodekloud/simple-prompt-docker
docker run –i kodekloud/simple-prompt-docker
docker run –it kodekloud/simple-prompt-docker

Run – PORT mapping
docker run kodekloud/webapp
docker run –p 80:5000 kodekloud/simple-webapp
docker run –p 8000:5000 kodekloud/simple-webapp
docker run –p 8001:5000 kodekloud/simple-webapp
docker run –p 3306:3306 mysql
docker run –p 8306:3306 mysql
docker run –p 8306:3306 mysql


RUN – Volume mapping
docker run mysql
docker stop mysql
docker rm mysql
docker run –v /opt/datadir:/var/lib/mysql mysql

Inspect Container
docker inspect blissful_hopper

Container Logs
docker logs blissful_hopper



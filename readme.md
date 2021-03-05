### build image
docker build -t rendra/simple-backend .

### run docker
docker run -p 4000:4000 rendra/simple-backend

### List images
docker images

### List container
docker ps 

### stop container
docker stop [id xxxx]

docker push
docker pull

docker image inspect 72872485c491

check images Operating System
docker run -it rendra/simple-backend cat /etc/os-release

gh repo create docker-simple
gh repo view -w

### docker-compose
docker-compose build

docker-compose up -d mongo

### display logs
docker logs [container-id] -> `docker logs 8c63`

### run app container
docker-compose up -d app

### stop docker compose
docker-compose stop

---
Frontend
### build frontend image
docker build -t rendra/frontend .

### delete image
docker rmi [IMAGE-ID]
 
### run image
docker run -p 3000:3000 rendra/frontend

### stop container
docker stop [id xxxx]

### pull images from docker hub
docker pull ruby:2.7.2

### delete un-used volumes
docker system prune -a --volumes
or 
docker system prune --volumes

## up
docker-compose up

### check disk usage
docker system df

## up
docker-compose up -d mongo
### down, delete volume
docker-compose down -v

### list docker volume
docker volume ls

### usefull links
https://www.codenotary.com/blog/extremely-useful-docker-commands/

---
### docker workflow
https://karlcode.owtelse.com/blog/2017/01/25/push-a-docker-image-to-personal-repository/ 
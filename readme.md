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
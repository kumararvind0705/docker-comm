yum install docker -y
docker search
docker images
docker info
docker --version
docker pull
docker run -it --name arvind ubuntu bin/bash
service docker start 
service docker attach
service docker status
docker ps
docker ps -a
docker diff contername
docker commit
docker build -t volume newvolume
docker run -name --it arvind -v/volume ubuntu /bin/bash
docker run -it --name arvind -v/volume --privileged=true ubuntu /bin/bash
docker run -td --name servertd -p 80:80 ubuntu
apt-get update -y
apt-get install apache2 -y
docker login
images delete  
docker rmi -f $(docker images -q)
docker rm -rf contenar name




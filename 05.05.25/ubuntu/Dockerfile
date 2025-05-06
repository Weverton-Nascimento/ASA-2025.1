
FROM ubuntu:latest

# instalar ferreamentas de teste de rede

RUN apt update 

RUN apt upgrade -y 

RUN apt install -y net-tools dnsutils iputils-ping 

RUN apt install openssh-server -y

CMD ["/usr/bin/tail", "-f", "/dev/null"]

# criar imagem docker 
    # docker build -t my-image .

# criar container 
    # docker run -it --name my-container my-image

#criar rede 
    # docker network create -d bridge net-ubuntu

#criar  imagem ssh
    # docker build -t my-ubuntu-image-ssh .

#docker run -d --net=net-ubuntu --name ubt003 my-ubuntu-image-ssh

FROM debian:latest

# instalar ferreamentas de teste de rede

RUN apt update 

RUN apt upgrade -y 

RUN apt install -y net-tools dnsutils iputils-ping

RUN apt install openssh-server -y

# manter execuçao do container
CMD ["/usr/bin/tail", "-f", "/dev/null"]

# adicionar usuario
RUN useradd -m redes

# senha de usuario
RUN echo "redes:redes"|chpasswd

# criar imagem docker 
    # docker build -t my-image .

# criar container 
    # docker run -it --name my-container2 my-image-debian

#criar rede 
    # docker network create -d bridge net-debian

#criar  imagem ssh
    # docker build -t my-debian-image-ssh .

#docker run -d --net=net-debian --name ubt003 my-debian-image-ssh
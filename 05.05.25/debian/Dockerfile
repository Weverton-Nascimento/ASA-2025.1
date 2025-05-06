
FROM debian:latest

# instalar ferreamentas de teste de rede

RUN apt update 

RUN apt upgrade -y 

RUN apt install -y net-tools dnsutils iputils-ping

CMD ["/usr/bin/tail", "-f", "/dev/null"]

# criar imagem docker 
    # docker build -t my-image .

# criar container 
    # docker run -it --name my-container2 my-image-debian

#criar rede 
    # docker network create -d bridge net-debian
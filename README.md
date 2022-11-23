# cs2080_16NovBM

#I do not know how to use github so I am just copying my docker file into the readme.

FROM ubuntu
RUN apt-get -y update
RUN apt install -y zsh
RUN curl -fsSL https://code-server.dev/install.sh | sh 
EXPOSE 80


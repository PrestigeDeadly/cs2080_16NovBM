# cs2080_16NovBM

#I dont know how to move files from the code space into my repository. I do not know
#how to do anything on github so i will just be copying and pasting the docker file.

FROM ubuntu
RUN apt-get -y update
RUN apt install -y zsh
RUN curl -fsSL https://code-server.dev/install.sh | sh 
EXPOSE 80

**Command to run**
docker run -itd -p 80 --name vsCode ~/context

# Docker in a Month of Lunches
This my repo with the work along code for the book DIAMOL by Elton Stoneman

docker container run --interactive --tty diamol/base

docker container ls --all --quiet

docker container run --detach --publish 3000:80 diamol/ch02-hello-diamol-web

docker container rm --force $(docker container ls --all --quiet)

docker container stats 

docker container logs 7c


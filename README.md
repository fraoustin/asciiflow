# Docker Image for asciiflow

generate a nginx server with asciiflow2 application

You can use client

- ihm on http://127.0.0.1/ 


load when start image load file in

- /usr/share/gitweb/docker-entrypoint.pre
- /usr/share/gitweb/docker-entrypoint.post

## Parameter

- SET_CONTAINER_TIMEZONE (false or true) manage time of container
- CONTAINER_TIMEZONE timezone of container

## Volume

- /share

## Port

- 80 

## Usage direct

run image fraoustin/asciiflow

    docker run -d --name asciiflow -p 80:80 fraoustin/asciiflow

you use http://localhost/ for access ihm

## Usage by Dockerfile

clone

    git clone https://github.com/fraoustin/asciiflow.git

build image asciiflow

    docker build -t asciiflow .

## External library

- asciiflow2 on https://github.com/lewish/asciiflow2



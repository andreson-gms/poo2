# AMBIENTE

## UDATE SERVE HOST

    docker info
    docker ps --a

## MARKDOWN

    docker rm -f ...
    docker image rm ... 

## AMBIENTE DOCKER PARA BANCO DE DADOS

    docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres

## ACESSAR BASH DO CONTAINER

    docker exec -it some-postgres bash

## LOGAR NO POSTGRES

    psql -U postgres

## CRIAR BD

    

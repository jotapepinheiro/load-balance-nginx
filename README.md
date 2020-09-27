# Load Balance com Nginx (3 Nodes)

## Iniciar Docker

- docker-compose up -d

## Desligar Docker

- docker-compose down

## Listar Containers

- docker-compose ps -a

## Adicionar Bash e Nano no Container

- docker-compose exec nginx apk add bash nano

## Acessar o Container

- docker-compose exec nginx bash

## Verificar Configuraçõs do Nginx

- nginx -t

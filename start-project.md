## Comandos Importantes para inicar o projeto

- Inicío das imagens existentes no docker-compose e libera o terminal: 

docker-compose up -d

- docker-compose exec será executado dentro de seu contêiner de serviço existente em execução, enquanto a execução de docker-compose iniciará um novo contêiner independente:

docker-compose exec app bash

docker exec -it 'nome do container criado' bash (para entrar dentro do container)

docker stop $(docker ps -a -q) #stop all running containers

- Criando Go Mod (gerenciador de dependências do Golang):

1. Vá a pasta que será seu módulo do projeto e rode:
 
go mod init 'nome do módulo'



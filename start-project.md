## Comandos Importantes para inicar o projeto

- Inicío das imagens existentes no docker-compose e libera o terminal: 

docker-compose up -b

- docker-compose exec será executado dentro de seu contêiner de serviço existente em execução, enquanto a execução de docker-compose iniciará um novo contêiner independente:

docker-compose exec app bash

- Criando Go Mod (gerenciador de dependências do Golang):

1. Vá a pasta que será seu módulo do projeto e rode:
 
go mod init 'nome do módulo'



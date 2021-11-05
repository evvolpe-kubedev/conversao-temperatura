# Conversão de Temperatura
Sistema conversor de  Celsius para Fahrenheit e vice-versa.

# Build da imagem

Executar as linhas de comando abaixo dentro da pasta /src: </br></br>
`docker build -t evvolpe/conversao-temperatura .`</br>
`docker push evvolpe/conversao-temperatura`</br></br>
Os comandos executados acima vão construir uma imagem e a armazenar no Docker Hub </br></br>

# Executando o container

Executar a linha de comando para executar o container com a imagem que geramos e armazenamos na nuvema: </br></br>
`docker run -d evvolpe/conversao-temperatura`</br></br>
Para listar o container em execução: </br>
`docker container ls` </br></br>
Para listar os containers parados use:</br>
`docker container ls -a` </br>

#Verificando a imagem enviada para o docker Hub
[Clique aqui para verificar a imagem no Hub](https://hub.docker.com/repository/docker/evvolpe/conversao-temperatura)

# Alô Mundo Java Docker

Projeto de teste em Java 8, empacotado com Maven e containerizado com Docker.

## Como rodar

Compilar e empacotar:
mvn clean package

Build da imagem Docker:
docker build -t alomundo_java_docker .

Rodar o container:
docker run alomundo_java_docker

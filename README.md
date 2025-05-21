Projeto Docker com NGINX, HTML E CSS 

 Objetivo do projeto 

Criar um ambiente de hospedagem web local utilizando Docker e Nginx, com uma página HTML sobre recursos do Docker com algumas estilizações em CSS.

Comandos utilizados neste projeto
```bash
docker build -t avaliacao-pratica .
docker run -d -p 8080:80 avaliacao-pratica
docker ps
docker logs + ID do Container
```

Como executar o container

Clone o repositório:

git clone https://github.com/MrMatheusMotta/avaliacao-pratica-docker.git

Acesse a pasta e execute no terminal :

docker build -t avaliacao-pratica .

docker run -d -p 8080:80 avaliacao-pratica

Acesse no navegador:

http://localhost:8080

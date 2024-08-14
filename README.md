# Aula de banco do mestre Andreo 🤠🥋

Vamos utilizar o [PostgreSql](https://www.postgresql.org/docs/) como linguagem de banco de dados.

## Instalando

Vamos utilizar Docker ([uma plataforma de container para simular as dependencias do banco](https://www.hostinger.com.br/tutoriais/o-que-e-docker))
para subir uma imagem postgres a partir do arquivo [docker-compose.yml](/docker-compose.yml).

1. Primeiro passo é baixar o docker para a maquina: [Nesse link](https://www.docker.com/products/docker-desktop/)
2. Instale ele normalmente (Possivelmente vai pedir pra reiniciar)
3. Abra o terminal do windows
4. navegue até a pasta que está o arquivo `docker-compose.yml` utilizando o comando cd
   1. Exemplo: `cd Desktop`
5. use o comando `docker compose up -d` 
6. Faça o download de um dos [SGBD's](https://www.treinaweb.com.br/blog/o-que-e-um-sgbd#:~:text=Data%20Base%20Management%20System%20ou,as%20bases%20de%20dados%20utilizadas) abaxo:
    - PgAdmin: [DOWNLOAD](https://www.pgadmin.org/download/)
    - DataGrip: [DOWNLOAD](https://www.jetbrains.com/pt-br/datagrip/)
7. Crie uma conexão do banco de dados
8. Toda vez que reiniciar, precisa rodar de novo o comando `docker compose up -d`



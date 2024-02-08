# Setup de Banco de Dados PostgreSQL com Docker
Desafio 01 - Banco de Dados Postgresql:
```bash
docker container run -d -p 5432:5432 --name postgresql -e POSTGRES_DB="curso_docker" -e POSTGRES_USER="docker_usr" -e POSTGRES_PASSWORD="docker_pwd" postgres

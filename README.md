# Setup de Banco de Dados PostgreSQL com Docker
Comando simples para criar um banco de dados PostgreSQL em um ambiente de desenvolvimento usando Docker. O comando abaixo cria um contêiner PostgreSQL com as configurações necessárias:
```bash
docker container run -d -p 5432:5432 --name postgresql -e POSTGRES_DB="curso_docker" -e POSTGRES_USER="docker_usr" -e POSTGRES_PASSWORD="docker_pwd" postgres

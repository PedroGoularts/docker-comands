# docker-comands
docker basics comands

- Create database postgres + enviroment variables
docker run -p 5432:5432 --name db_postgress -e POSTGRES_USER=docker_usr -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_DB=curso_docker  -d postgres

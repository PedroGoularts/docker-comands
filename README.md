# docker-comands
docker basics comands

- Create database postgres + enviroment variables:
  
docker run -p 5432:5432 --name db_postgress -e POSTGRES_USER=docker_usr -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_DB=curso_docker  -d postgres

Results:

![Desafio 01](https://uploaddeimagens.com.br/images/004/787/931/original/desafio01.png?1716774484)

- Create database mysql + enviroment variables:

docker run -p 3306:3306 --name db_mysql -e MYSQL_ROOT_PASSWORD=docker_pwd -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -d mysql

![Desafio 02](https://uploaddeimagens.com.br/images/004/791/895/original/mysql.png?1717464123)

- Create database mongo + enviroment variables:

docker run -p 8081:8081 --name db_mongo -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd -d mongo

![Desafio 03](https://uploaddeimagens.com.br/images/004/791/897/original/mongodb.png?1717464919)
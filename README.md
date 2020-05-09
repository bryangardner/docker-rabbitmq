# docker-rabbitmq
* Build: `docker build --tag docker-rabbitmq:latest .`
* Start: `docker run -d --hostname my-rabbit --name some-rabbit -p 8080:15672 -p 61613:61613 docker-rabbitmq:latest`

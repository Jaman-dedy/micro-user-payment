# NESTJS MICROSERVICE MYSQL

This is the main repository that includes submodules for individual components.

## Http gateway

### [Http-gateway](https://github.com/Jaman-dedy/http-api-gateway)

- Description: The http gateway to will communicate with nats server and publish events

## Microservices

### [Users-microservice](https://github.com/Jaman-dedy/users-microservice)

- Description: The users microservice that will listen to event from nats server.

### [Payments-microservice](https://github.com/Jaman-dedy/payments-microservice)

- Description: The payments micro service that will listen to event from nats sever.

## Microservice schema 

 Clients ---> http-gateway -----> microservices ----- mysql-db


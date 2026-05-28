
# Spring Cloud Config Example

## Modules

- config-server
- user-service
- config-repo

## Run Config Server

```bash
cd config-server
mvn spring-boot:run
```

## Run User Service

```bash
cd user-service
mvn spring-boot:run
```

## Test

Open:

- http://localhost:8888/user-service/default
- http://localhost:8081/message

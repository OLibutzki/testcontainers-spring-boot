# Demo
[![MavenBuild](https://github.com/sparsick/testcontainers-spring-boot/actions/workflows/build.yml/badge.svg)](https://github.com/sparsick/testcontainers-spring-boot/actions/workflows/build.yml)

Spring Boot Demo Application

```
mvn clean install
mvn spring-boot:run
```

Application URL: `http://localhost:8080/hero`

A database is needed

```
docker run --name my-sql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=my-secret-pw -e MYSQL_DATABASE=test -e MYSQL_USER=user -e MYSQL_PASSWORD=pwd -d mysql
```

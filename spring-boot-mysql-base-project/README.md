# Spring Boot MySQL Base Project

This application was developed to demonstrate Spring Boot with MySQL with simple API.

Technologies Used

- Spring Boot 2.4.1
- Spring Data JPA
- Lombok
- MySQL
- Postgresql

How to Run this application

First change the **src/main/resources/application.properties** with your MySQL instance properties.

Then,

Navigate to application root folder and execute,

```shell
$ ./gradlew clean build
```

Now there should be a newly created jar file with all the necessary files to run this application on build/libs folder.
Then create the build with docker compose to build docker image using built jar file.


```shell
$ docker-compose build
```

Then start the JAR file using java

```shell
$  docker-compose up
```
Then It will capture the docker-compose.yml and start running using the instructions given on that file.

Reference: https://javatodev.com/docker-compose-spring-boot-postgresql/

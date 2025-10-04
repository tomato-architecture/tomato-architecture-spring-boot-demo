# tomato-architecture-spring-boot-demo
A sample Spring Boot application following [Tomato Architecture](https://tomato-architecture.github.io/)

## Prerequisites
* JDK 25
* Docker Compose

## TechStack
* Java 25
* Spring Boot
* Spring Modulith
* jOOQ
* PostgreSQL
* Kafka
* Testcontainers
* Docker Compose

## How to run?
The application is configured to use Docker Compose to start the dependent services (Postgres, Kafka).
You can simply run `BookStoreApplication.java` from your IDE to start the application.

**NOTE:** To work with Kafka transparently from both local and container, add `127.0.0.1   broker` entry in `/etc/hosts` file.

You can also start the application from commandline as follows:

```shell
$ ./mvnw spring-boot:run
```

## Run tests
You can run the tests as follows:

```shell
$ ./mvnw test
```

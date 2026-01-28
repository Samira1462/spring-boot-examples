# Read Me First
The following was discovered as part of building this project:

* The original package name 'com.tutorial.messaging-apache-kafka' is invalid and this project uses 'com.tutorial.messagingapachekafka' instead.

# Getting Started

### Prerequisites
For further reference, please consider the following sections:

* [Spring Web](https://docs.spring.io/spring-boot/4.0.1/reference/web/servlet.html)
* [Spring for Apache Kafka](https://docs.spring.io/spring-boot/4.0.1/reference/messaging/kafka.html)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/4.0.1/reference/actuator/index.html)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/4.0.1/reference/using/devtools.html)
* Docker
* Java 21
* Maven 3.8.4

### Build
```
mvn validate clean compile -DskipTests=true 

```
### Test
```
mvn test

```
### Package
```
mvn package -DskipTests=true

```
### Run

```
mvn  spring-boot:start

```
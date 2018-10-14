# Getting Started with Spring Boot - Example Application

https://getting-started-spring-boot.herokuapp.com/

[![CircleCI](https://circleci.com/gh/johnboyes/gs-spring-boot.svg?style=svg)](https://circleci.com/gh/johnboyes/gs-spring-boot)
[![Heroku](http://heroku-badge.herokuapp.com/?app=getting-started-spring-boot&svg=1&root=/actuator/health)](https://getting-started-spring-boot.herokuapp.com/)

The example application from the Spring Boot website: https://spring.io/guides/gs/spring-boot

## Running the application

### Prerequisites

* [Maven](https://maven.apache.org/)

### Command to start the application

`mvn package && java -jar target/gs-spring-boot-0.1.0.jar`


## Running the tests

### Running the unit tests

`mvn test`

### Running the integration tests

`mvn verify`


## Continuous Integration

[Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration) is on [CircleCI](https://circleci.com/product/): https://circleci.com/gh/johnboyes/gs-spring-boot

## Deploying the application

The app deploys automatically to [Heroku](https://getting-started-spring-boot.herokuapp.com/) via the CI/CD pipeline.

# Spring Security Login Tutorial

1. mvn clean install
2. java -jar target/login-tutorial.jar

- http://localhost:8080/registration
- http://localhost:8080/login

### Docker
- mvn clean install
- docker build --tag login-tutorial .
- docker run --net=host login-tutorial 
# Spring Boot Hello World

[こっからコピーしてきました](https://github.com/gazgeek/springboot-helloworld)

A spring boot enabled hello world application

- Travis CI build and test
- Continuous deployment to Heroku on success

## Usage

- Directly using maven

```sh
mvn spring-boot:run
```

- From within your IDE right click run

```sh
Application.java
```

- From executable jar file

```sh
mvn clean install
java -jar target/helloworld-0.0.1-SNAPSHOT.jar
```

- To run this as a docker application (assumption docker is installed on your machine)

```sh
docker pull keropon48/citest
docker container run -p 8080:8080 -d keropon48/citest

Go to Browser and type http://localhost:8080/ or do curl http://localhost:8080/ on command prompt
```

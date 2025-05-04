FROM openjdk:17-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ./target/userservice-0.0.1-SNAPSHOT.jar .
ENTRYPOINT ["java", "-jar", "userservice-0.0.1-SNAPSHOT.jar"]
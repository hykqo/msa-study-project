FROM openjdk:17-ea-11-jdk-slim
VOLUME /tmp
COPY /target/*-1.0-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar","app.jar"]
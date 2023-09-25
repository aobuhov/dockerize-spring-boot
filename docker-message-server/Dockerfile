FROM openjdk:17
MAINTAINER example.com
COPY target/docker-message-server-1.0.0.jar message-server-1.0.0.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/message-server-1.0.0.jar"]

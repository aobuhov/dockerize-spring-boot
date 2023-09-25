FROM openjdk:17
MAINTAINER example.com
COPY target/docker-product-server-1.0.0.jar product-server-1.0.0.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/product-server-1.0.0.jar"]

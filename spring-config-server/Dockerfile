FROM openjdk:11.0.3-jdk-stretch
ADD ./target/spring-config-server-0.0.1-SNAPSHOT.jar /app/microservices/spring-config-server-0.0.1-SNAPSHOT.jar
WORKDIR /app/microservices
ENTRYPOINT ["java","-jar","spring-config-server-0.0.1-SNAPSHOT.jar"]
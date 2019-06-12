FROM openjdk:11.0.3-jdk-stretch
ADD ./target/user-service-0.0.1-SNAPSHOT.jar /app/microservices/user-service-0.0.1-SNAPSHOT.jar
WORKDIR /app/microservices
ENTRYPOINT ["java","-jar","user-service-0.0.1-SNAPSHOT.jar"]
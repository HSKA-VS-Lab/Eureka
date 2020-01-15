FROM openjdk:8-jdk-alpine
ADD target/Eureka-*.jar eureka.jar
EXPOSE 8090
ENTRYPOINT ["java","-jar", "eureka.jar"]
FROM openjdk:8
ADD target/Eureka-*.jar eureka.jar
EXPOSE 8090
ENTRYPOINT ["java","-jar", "eureka.jar"]
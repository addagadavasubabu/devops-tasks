# used java 16 as the base image
FROM openjdk:16

# Copying the artifact(jar file) from local to the container
COPY target/spring-boot-angular-1.0.jar spring-boot-angular-1.0.jar

# adding ENTRYPOINT command to start the application
ENTRYPOINT ["java","-jar","/spring-boot-angular-1.0.jar"]
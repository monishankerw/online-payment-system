FROM openjdk:17-jdk-slim
WORKDIR /app
COPY build/libs/userServices.jar userServices.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "userServices.jar"]
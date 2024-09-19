FROM openjdk:17

ARG JAR_FILE=target/*.jar

ADD ${JAR_FILE} chat-service.jar

ENTRYPOINT ["java", "-jar", "chat-service.jar"]

EXPOSE 8090
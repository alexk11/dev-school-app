FROM openjdk:8

ARG JAR_FILE=build/libs/dev-school-app-1.0-SNAPSHOT.jar

WORKDIR /app

COPY ${JAR_FILE} backend-server.jar

ENTRYPOINT ["java", "-jar", "backend-server.jar"]

EXPOSE 8081
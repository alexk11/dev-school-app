FROM openjdk:8

ARG JAR_FILE=./devschool-front-app-server/build/libs/devschool-front-app-server-1.0.0.jar

COPY ${JAR_FILE} frontend-server.jar

ENTRYPOINT java -jar frontend-server.jar -P:ktor.backend.host=${BACKEND_HOST}

EXPOSE 8080
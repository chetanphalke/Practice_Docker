FROM openjdk:8-jdk-alpine

COPY target/erp-inbox-be-docker.jar DaVitaAuthServer.jar

EXPOSE 8081
ENTRYPOINT ["java", "-jar", "DaVitaAuthServer.jar"]

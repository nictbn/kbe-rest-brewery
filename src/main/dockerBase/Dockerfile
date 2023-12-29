FROM openjdk:11-jre-slim

ENV JAVA_OPTS " -Xms512m -Xmx512m -Djava.security.egd=file:/dev/./urandom"

COPY ../../../target/*.jar ./kbe-rest-brewery.jar
ENTRYPOINT ["java", "-jar", "kbe-rest-brewery.jar"]
FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY build/libs/*.jar -t monitoring/sandbox .
ENTRYPOINT ["java", "-jar", "/app.jar"]

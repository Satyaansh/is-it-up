FROM --platform=linux/arm64/v8 openjdk:17-alpine
VOLUME /tmp
COPY build/libs/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
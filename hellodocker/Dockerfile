FROM openjdk:11

ARG jarToCopy

COPY /target/$jarToCopy /app/app.jar

CMD ["java", "-cp", "/app/app.jar", "com.examples.hellodocker.App"]
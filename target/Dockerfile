FROM openjdk:8-jdk-alpine
COPY --from=build /home/target/hello-0.0.1-SNAPSHOT.jar SpringBootFormExample-1.0.jar
ENTRYPOINT ["java", "-jar", "/SpringBootFormExample-1.0.jar"]

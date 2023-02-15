FROM openjdk:8-jdk-alpine
ARG JAR_FILE=home/target/*.jar
COPY ${JAR_FILE} test-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/test-0.0.1-SNAPSHOT.jar"]

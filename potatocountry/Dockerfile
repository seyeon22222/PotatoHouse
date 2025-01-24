FROM openjdk:21-jdk

WORKDIR /app

ARG JAR_FILE=build/libs/potatocountry-Test.jar

COPY ${JAR_FILE} .

ENTRYPOINT ["java","-jar","potatocountry-42gg.jar"]
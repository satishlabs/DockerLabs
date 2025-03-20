FROM openjdk:17
EXPOSE 8080
#compy app.jar from target to docker with same name
ADD target/app.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]


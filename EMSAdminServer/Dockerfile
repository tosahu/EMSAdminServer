FROM openjdk:latest
ADD /target/*.jar adminserver.jar
EXPOSE 9999
ENTRYPOINT ["java","-jar","/adminserver.jar"]
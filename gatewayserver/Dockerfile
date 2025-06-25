# Step 1: Use the official OpenJDK image as the base image
FROM openjdk:21-jdk-slim

#Info around who maintain the image
#MAINTAINER zeroo8.com

#Add the application jar to the image
COPY target/gatewayserver-0.0.1-SNAPSHOT.jar gatewayserver-0.0.1-SNAPSHOT.jar

#Execute the application
ENTRYPOINT ["java", "-jar", "gatewayserver-0.0.1-SNAPSHOT.jar"]

# Use an official Java runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /usr/app

# Copy the compiled JAR file into the container
COPY target/demo-0.0.1-SNAPSHOT.jar /usr/app/demo.jar

# Run the JAR file
ENTRYPOINT ["java", "-jar", "demo.jar"]

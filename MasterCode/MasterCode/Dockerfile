# Use a minimal Java runtime base image
FROM openjdk:17-jdk-slim

# Set working directory inside container
WORKDIR /app

# Copy jar file into the container
COPY target/MasterCode-0.0.1-SNAPSHOT.jar app.jar

# Expose the port your app runs on (change if needed)
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]

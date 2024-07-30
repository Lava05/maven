# Use OpenJDK 17 base image
FROM openjdk:17

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# Expose port 8080
EXPOSE 8080

# Command to run the JAR file
CMD ["java", "-jar", "app.jar"]

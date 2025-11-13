# Use OpenJDK base image
FROM openjdk:17-jdk-slim

# Copy jar file from target
COPY target/*.jar app.jar

# Expose Eureka server port
EXPOSE 8761

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]

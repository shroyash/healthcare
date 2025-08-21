# Use official OpenJDK 17 image
FROM eclipse-temurin:21-jdk-jammy

# Set working directory
WORKDIR /app

# Copy Maven built JAR into container
COPY target/config-service-0.0.1-SNAPSHOT.jar app.jar

# Expose port
EXPOSE 8000

# Run the JAR
ENTRYPOINT ["java","-jar","app.jar"]
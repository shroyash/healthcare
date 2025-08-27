# Use official OpenJDK 21 image
FROM eclipse-temurin:21-jdk-jammy

# Set working directory
WORKDIR /app

# Copy Maven built JAR into container
COPY target/discovery-server-0.0.1-SNAPSHOT.jar app.jar

# Expose port
EXPOSE 8761

# Run the JAR
ENTRYPOINT ["java","-jar","app.jar"]




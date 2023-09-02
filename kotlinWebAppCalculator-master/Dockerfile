# Use the official OpenJDK image as the base image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled KotlinWebAppCalculator-master JAR file into the container
COPY kotlinWebAppCalculator-master/build/libs/KotlinWebAppCalculator-master.jar app.jar

# Expose the port that your web app is listening on
EXPOSE 8080

# Command to run your application
CMD ["java", "-jar", "app.jar"]

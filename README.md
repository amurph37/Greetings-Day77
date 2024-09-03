Greetings Application

Purpose
The Greetings Application is a simple Spring Boot project designed to demonstrate the creation and deployment of a RESTful web service. This service provides a basic greeting message when accessed via an HTTP GET request. The application serves as an introductory example of how to use Spring Boot to create a REST API.

Features
- A single REST endpoint (`/greeting`) that returns a "Hello, World!" message.

Prerequisites
- **Java 22** installed on your machine
- **Maven** for managing dependencies and building the application
- **IntelliJ IDEA** (or any Java IDE) for development
- **Postman** (optional, for testing the API)

Getting Started

1. Use Spring Initializr for the Project Structure
   - Project: Maven
   - Language: Java
   - Spring Boot Version: 3.3.3
   - Project Metadata: Group: com.example -- Artifact: greetings -- Name: greetings -- Package Name: com.example.greetings -- Packaging: Jar -- Java Version: 22 -- Dependencies: Spring Web dependency.

Use Maven to clean and build the project
- mvn clean install

To run the application, I used my IDE (Right-clicking file then selecting RUN) but you can also run the application by using the Maven code below in your terminal.
- mvn spring-boot:run

You can access the application by opening your web browser and navigating to - http://localhost:8080/greeting

I tested the application by using Postman.
- Open Postman.
- Create a new GET request.
- Enter the following URL: http://localhost:8080/greeting.
- Click the Send button.
- You should receive a 200 OK response with the body: Hello, World!.

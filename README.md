# Demo Spring Boot Application

This is a simple Spring Boot application that demonstrates a basic RESTful endpoint.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Java Development Kit (JDK) version 8 or higher**
- **Maven**
- **An Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or Visual Studio Code**

## Project Setup

### 1. Create a New Spring Boot Project

1. Go to [Spring Initializr](https://start.spring.io).
2. Fill in the project metadata:
   - **Project:** Maven Project
   - **Language:** Java
   - **Spring Boot:** Latest stable version
   - **Group:** `com.example`
   - **Artifact:** `demo`
   - **Name:** `demo`
   - **Package name:** `com.example.demo`
   - **Packaging:** Jar
   - **Java:** 11 (or your preferred version)
3. Add the following dependencies:
   - Spring Web
   - Spring Boot DevTools
   - Lombok (optional)
4. Click "Generate" to download the project as a zip file.
5. Unzip the project to your preferred location.

### 2. Import the Project into Your IDE

1. Open your IDE.
2. Import the unzipped project as a Maven project.
3. Ensure the IDE is configured to use the correct JDK.

## Running the Application

### Using Your IDE

1. Navigate to `src/main/java/com/example/demo/DemoApplication.java`.
2. Right-click on `DemoApplication.java` and select "Run".

### Using the Command Line

1. Open a terminal and navigate to the project directory.
2. Run the command:

   ```sh
   ./mvnw spring-boot:run

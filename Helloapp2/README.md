# HelloApp

A simple Maven-based Java project that greets users.

## Prerequisites

- Java 11 or higher
- Apache Maven 3.6 or higher

## Building the Project

To compile the project, run:

```bash
mvn compile
```

## Running the Application

To run the application without arguments:

```bash
mvn exec:java
```

This will output: `Hello, World!`

To run with names:

```bash
java -cp target/classes com.helloapp.HelloApp Alice Bob
```

This will output: `Hello, Alice, Bob!`

## Project Structure

- `src/main/java/com/helloapp/HelloApp.java` - Main application class
- `pom.xml` - Maven project configuration

## Dependencies

- JUnit 4.13.2 (for testing)
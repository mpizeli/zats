# ZATS Sample Application

This is a sample application using the ZATS Java testing framework for ZK applications.

## Project Structure

- **pom.xml**: Maven configuration for managing dependencies and build process.
- **src/main/webapp/index.zul**: Defines the main UI window and components.
- **src/test/java/com/example/ZATSTest.java**: Contains JUnit test cases using the ZATS framework.

## Dependencies

The application relies on the following dependencies:
- **ZK Framework**: ZK, ZUL, ZK+ are used for building the UI.
- **ZATS Mimic**: Testing framework for ZK applications.
- **JUnit**: Framework for writing unit tests.
- **SLF4J**: Logging API.

## Running the Application

You can run the application using Maven:
```bash
mvn clean install
```

## Running the Tests

Tests are located in `src/test`, and you can run them with:
```bash
mvn test
```

## Author

- Your Name


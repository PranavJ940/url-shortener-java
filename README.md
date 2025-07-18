# url-shortener-java
# URL Shortener (Java, No Frameworks)

## Overview
A simple URL shortener service inspired by TinyURL, built with Java's built-in HTTP server, H2 database, and a plain HTML/CSS/JS frontend. No frameworks are used.

## Features
- Anonymous URL shortening
- User registration and login
- Custom short URLs for logged-in users
- Redirection from short URL to original
- Simple, functional UI (no frameworks)
- Logging with SLF4J
- Unit tests with JUnit 5 and Mockito

## Tech Stack
- **Backend:** Java (`com.sun.net.httpserver.HttpServer`), JDBC, H2 Database
- **Frontend:** HTML, CSS, JavaScript (no frameworks)
- **Logging:** SLF4J
- **Testing:** JUnit 5, Mockito
- **CI/CD:** GitHub Actions

## Requirements
- No frameworks (Spring, Tomcat, Angular, React, etc.)
- Use only plain Java, HTML, CSS, JS
- Use H2 Database for storage
- Use SLF4J for logging
- Use JUnit 5 and Mockito for testing
- Use GitHub Issues, Branches, Pull Requests, and Actions for workflow

## Setup Instructions

### Prerequisites
- Java 11 or higher
- Maven (for build and dependency management)

### Running the Application
1. Clone the repository:
   ```sh
   git clone https://github.com/PranavJ940/url-shortener-java.git
   cd url-shortener-java
   ```
2. Build the project:
   ```sh
   mvn clean package
   ```
3. Run the server:
   ```sh
   java -jar target/url-shortener-java.jar
   ```
4. Open `index.html` in your browser (or navigate to the server's address if serving static files).

### Running Tests
```sh
mvn test
```

## Development Workflow
- Use GitHub Issues to track features and bugs
- Use feature branches for each task
- Open Pull Requests for code review and merging
- GitHub Actions will run build and tests on every PR and merge

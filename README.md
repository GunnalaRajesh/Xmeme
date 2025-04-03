# QMoney - Spring Boot Template

This repository serves as a template for initializing and running Spring Boot projects.

## What's Included

1. **Gradle Build System** - Created from [start.spring.io](https://start.spring.io/)
2. **Plugins Integrated**
   - SpotBugs (Static Code Analysis)
   - Checkstyle (Code Formatting & Quality Checks)
   - Jacoco (Code Coverage Reports)
3. **Dependencies Pre-configured**
   - MongoDB
   - MySQL
   - Redis
4. **Docker Support**
   - Dockerfile to start MongoDB server
   - Runs the Spring Boot application within a container

---

## Usage

### Building the Repository

From the root directory of the repository:

1. **Build and Run Tests**
   ```bash
   ./gradlew build test

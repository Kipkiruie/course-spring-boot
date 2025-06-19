# Course Spring Boot

Welcome to the ultimate Spring Boot learning repository! This course is designed to take you from a complete beginner in Spring Boot to building and deploying a REST API with a real database, Dockerizing it, and deploying it to the cloud.

---

## **About This Course**
This repository provides resources, examples, and projects to help you master Spring Boot. The course assumes prior knowledge of Java programming and focuses on:

- **Building a REST API:** Learn to create APIs that interact seamlessly with databases.
- **Real Database Integration:** Work with H2 and PostgreSQL databases.
- **Dockerization:** Package your application into a Docker container.
- **Cloud Deployment:** Deploy your application to AWS LightSail.

---

## **Modules**

1. **Quickstart**
   - Building the Quickstart App
   - Quickstart App Explainer

2. **Maven**
   - What is Maven?
   - Maven Concepts
   - Maven Project Structure
   - Maven Workflow
   - Maven Spring Boot Plugin

3. **Spring Framework & Boot**
   - Spring Framework vs Spring Boot
   - Spring App Layers
   - Modularity

4. **Dependency Injection**
   - Inversion of Control
   - Introducing Beans
   - @Component and Friends
   - Component Scanning
   - @SpringBootApplication Annotation
   - Autoconfiguration

5. **Configuration**
   - Configuration Files
   - Environment Variables
   - Configuration Properties

6. **Databases (Part 1: Basics)**
   - Database Layers
   - Connect to H2 and PostgreSQL Databases
   - Initialize Database Schema

7. **Databases (Part 2: DAOs with Spring JDBC)**
   - JDBCTemplate Setup
   - What is a DAO?
   - Create, Read, Update, Delete (CRUD) with DAOs
   - Integration Testing

8. **Databases (Part 3: Spring Data JPA)**
   - Setting Up Spring Data JPA
   - Entity Creation
   - Hibernate Auto DDL
   - CRUD Operations with Spring Data JPA
   - Custom Queries

9. **Jackson & JSON**
   - JSON and Spring Web
   - Java Objects to JSON
   - JSON to Java Objects
   - Renaming and Ignoring Properties

10. **Building a REST API**
    - REST API Design Principles
    - Creating, Testing, and Updating Endpoints
    - Handling Nested Objects
    - Pagination

11. **Deployment**
    - Dockerizing the Application
    - Deployment to AWS LightSail

---

## **Setup Instructions**

### **Prerequisites**
- Java Development Kit (JDK 11 or higher)
- Maven
- Docker (for containerization)
- AWS Account (for deployment)

### **Steps**
1. Clone this repository:
   ```bash
   git clone https://github.com/Kipkiruie/course-spring-boot.git
   ```

2. Navigate into the project directory:
   ```bash
   cd course-spring-boot
   ```

3. Build the project:
   ```bash
   mvn clean install
   ```

4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

5. Access the API locally at `http://localhost:8080`.

---

## **Acknowledgments**
Special thanks to the original creator of the course materials and the community contributors who make learning Spring Boot exciting and accessible.

---

## **License**
This repository is open for educational purposes. You are free to fork and contribute.

---

## **Author**
- **Elisha Ng'etich**
- GitHub: [Kipkiruie](https://github.com/Kipkiruie)
- Email: elishak551@gmail.com

Enjoy coding and mastering Spring Boot! 🚀


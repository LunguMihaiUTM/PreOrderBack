# PreOrderBack

## Overview
**PreOrderBack** is a backend application developed as part of an internship project at Orange. It manages preorders for a restaurant system, allowing users to place and manage their orders ahead of time. The project leverages Spring Boot, PostgreSQL, and Swagger for API documentation.

## Technologies Used
- ![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?logo=spring&logoColor=white) : Framework used to build the RESTful backend.
- ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql&logoColor=white) : Relational database to store orders and user information.
- ![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?logo=hibernate&logoColor=white) : ORM framework for database mapping.
- ![Liquibase](https://img.shields.io/badge/-Liquibase-2962FF?logo=liquibase&logoColor=white) : Database versioning and migrations.
- ![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?logo=swagger&logoColor=black) : Auto-generates API documentation.
- ![Maven](https://img.shields.io/badge/-Maven-C71A36?logo=apache-maven&logoColor=white) : Build tool for project dependencies.


## Features
- **User Authentication**: Secure login and registration system.
- **PreOrder Management**: Ability for users to create, update, and view preorders.
- **API Endpoints**: Multiple RESTful endpoints for interacting with the system.
- **Database Migrations**: Automatic schema updates using Liquibase.
- **Swagger Documentation**: Provides comprehensive API documentation for testing and integration.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/LunguMihaiUTM/PreOrderBack.git
    ```

2. **Install dependencies**:  
   This project uses Maven. Install dependencies by running:
    ```bash
    mvn install
    ```

3. **Configure the database**:
   - Ensure PostgreSQL is installed and running.
   - Update the `application.properties` or `application.yaml` file with your PostgreSQL connection details.

4. **Run the application**:
    Start the application with the following command:
    ```bash
    mvn spring-boot:run
    ```

5. **Access Swagger UI**:  
   After the application is running, navigate to the following URL to view the API documentation:
    ```bash
    http://localhost:8080/swagger-ui/
    ```

## API Documentation
Swagger is integrated into the project to provide auto-generated documentation. Access it by running the project and navigating to the `/swagger-ui/` page.

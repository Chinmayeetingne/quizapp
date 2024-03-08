Quiz Application Backend with Spring Boot
This project is a backend implementation of a quiz application using Spring Boot. It provides RESTful APIs for managing quizzes, questions, and answers.

Features
Create, read, update, and delete quizzes
Create, read, update, and delete questions within quizzes
Create, read, update, and delete answers within questions
Retrieve quiz results and statistics

Technologies Used
Spring Boot: Framework for building modern Java applications
Spring Data JPA: Simplifies database access and manipulation
Hibernate: ORM (Object-Relational Mapping) framework for mapping Java objects to database tables
PostgreSql: Relational database management system for data storage
Maven: Build automation tool for managing project dependencies and packaging

Project Structure
src/main/java: Java source code files
com.example.quizapplication: Main package for the application
controller: Contains controller classes for handling HTTP requests
model: Defines the data model classes (e.g., Quiz, Question, Answer)
repository: Spring Data JPA repositories for database access
service: Service layer classes for business logic
src/main/resources: Application properties and static resources

application.properties: Configuration file for database connection and other settings

# Book API - Living Letters

A RESTful web service built with Spring Boot to manage books for the fictional publishing house *"Letras Vivas"*.  
This API allows clients to perform basic operations such as listing, adding, searching, and deleting books.  
The project follows a layered architecture and professional coding practices.

---

## Features

- Retrieve all books
- Add a new book
- Search books by title
- Delete a book by its ID

---

## Technologies Used

- Java Zulu 17
- Spring Boot 
- Lombok
- Spring Data JPA
- H2 in-memory database
- Maven

---

## Project Structure

- model – Book entity class
- repository – Interface extending JpaRepository
- service – Business logic (interface + implementation)
- controller – REST endpoints
- resources – Contains configuration files like application.properties

---

## How to Run the Project

1. Download or clone the repository from GitHub:
   
   git clone https://github.com/jose23herrera/DESAFPRAC01_DWF
   
2. Open the project using *IntelliJ IDEA*.
3. Make sure you have Java 17 (Zulu) installed.
4. Build the project using Maven:
   
   mvn clean install
   
5. Run the application by executing the BookApiApplication.java file.
6. Once the application is running, you can access the endpoints:
   - API Base URL: http://localhost:8081/api/books
   - H2 Console (optional): http://localhost:8081/h2-console

---

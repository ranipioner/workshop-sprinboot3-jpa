# Spring Boot 3 + JPA Workshop

This is a demo project developed with **Spring Boot 3** and **Spring Data JPA**, using the **H2 in-memory database**. The goal of this project is to provide a hands-on learning experience with modern Spring Boot features, focusing on creating a simple backend RESTful service.
This project was made through Nelio Alves's Udemy Course "Java COMPLETO Programação Orientada a Objetos + Projetos"  @acenelio (Github)
## 🧰 Tech Stack

- Java 21
- Spring Boot 3.4.5
- Spring Web
- Spring Data JPA
- H2 Database (in-memory)
- Maven

## 📁 Project Structure

```
src/
├── main/
│ ├── java/
│ │ └── com.educandoweb.course/ # Main application package
│ └── resources/
│ ├── application.properties # Configuration
│ └── data.sql / schema.sql # (If present) DB initialization
└── test/

bash
Copiar
Editar

```
## 🚀 Getting Started

### Prerequisites

- Java 21
- Maven 3+

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/workshop-springboot3-jpa.git
   cd workshop-springboot3-jpa
   ```
   
2. Run the application with Maven:
 ```
./mvnw spring-boot:run
```

4. Access the application (e.g. APIs) via:
```
http://localhost:8080/
```
You can access the H2 database console (if enabled) at:

```
http://localhost:8080/h2-console
```
🧪 Running Tests
To execute unit tests:

```
./mvnw test
```
🎯 Learning Objectives
- Understand Spring Boot auto-configuration and project structure

- Practice building RESTful APIs with Spring Web

- Learn the fundamentals of Spring Data JPA

- Use H2 in-memory database for fast prototyping

📄 License
This project is for educational purposes and is not licensed for production use. Feel free to fork or use it for personal learning.

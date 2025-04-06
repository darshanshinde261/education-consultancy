# EduCon Full Stack Project

- This project is an education consultancy platform with a React frontend and a Spring Boot backend using Maven.

## 📁 Project Structure

# React frontend (Vite or CRA) 
- educon-front/
-  
# Spring Boot backend
- EduConProject/ 
- └── educationConsultancy/ 


---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- npm or yarn
- Java 17+
- Maven 3.6+
- PostgreSQL or MySQL (optional, depending on your DB config)

---

## 📦 Frontend Setup (`educon-front`)

```bash
- cd educon-front
- npm install     
- npm run dev     

## 📦 Frontend Setup (`EduConProject/educationConsultancy`)
- cd EduConProject/educationConsultancy
- ./mvnw spring-boot:run    # On Linux/macOS
- mvnw.cmd spring-boot:run  # On Windows

## Mysql setup
- spring.datasource.url=jdbc:postgresql://localhost:5432/yourdb
- spring.datasource.username=youruser
- spring.datasource.password=yourpass

## API + Frontend Connection
- create .env
- VITE_API_BASE_URL=http://localhost:8080/api



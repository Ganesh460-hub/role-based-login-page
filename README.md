# Role-Based Login System

A **Spring Boot** project demonstrating **role-based authentication** with **Admin, Teacher, and Student** roles using **Spring Security**. Ideal for showcasing backend skills on a resume.  

---

## Features

- Role-based login and dashboards  
- Secure authentication and authorization with Spring Security  
- SQL scripts for database setup with plaintext and bcrypt passwords  
- Clean MVC architecture with Thymeleaf templates  

---

## Tech Stack

- Java 17+ | Spring Boot | Spring Security | Maven  
- MySQL | HTML/Thymeleaf  

---

## Getting Started

1. **Clone the repository**  
```bash
git clone https://github.com/Ganesh460-hub/role-based-login-page.git
Import the project as a Maven project in IntelliJ or Eclipse.

Set up the database

Run the SQL scripts in sql-scripts/ to create users and roles.

Configure the database in src/main/resources/application.properties

properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_db_user
spring.datasource.password=your_db_password
spring.jpa.hibernate.ddl-auto=update
Run the application

bash
Copy code
mvn spring-boot:run
Open in browser:

arduino
Copy code
http://localhost:8080/
Author
Ganesh Nalla – Aspiring Java Backend Developer
GitHub Repository

yaml
Copy code

---

### **2️⃣ Save the file**

- Make sure it’s named exactly: `README.md`  
- Save it in your **project root folder** (the same folder where `pom.xml` is).  

---

### **3️⃣ Commit and push it to GitHub**

Open PowerShell in your project folder and run:

```powershell
git add README.md
git commit -m "Add professional README with setup instructions"
git push

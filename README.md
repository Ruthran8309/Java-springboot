
# 📚 Student Database Management System (DBMS) 🎓  

**StudentDBMS** is a **Spring Boot-powered** web application designed to manage student records efficiently. It provides a structured system for handling student data, courses, enrollments, grades, and attendance with seamless CRUD operations. This project leverages **Spring MVC, Spring Data JPA, and Thymeleaf** for an interactive and dynamic user experience.  

## 🚀 Features  

✅ **Student Management** – Add, update, delete, and retrieve student records.  
✅ **Course Management** – Manage courses and link students to their enrolled subjects.  
✅ **Enrollment System** – Students can enroll in and drop courses dynamically.  
✅ **Grades & GPA Calculation** – Assign grades and generate GPA reports.  
✅ **Attendance Tracking** – Log attendance and generate reports.  
✅ **Role-Based Access Control (RBAC)** – Secure authentication with **Spring Security** (Admin, Student, Instructor).  
✅ **RESTful API** – Exposes APIs for easy integration with other systems.  
✅ **Database Integration** – Uses **MySQL/PostgreSQL** with **Hibernate (JPA)** for efficient data persistence.  
✅ **Email Notifications** – Sends automatic email alerts for enrollments and grades.  

## 🛠️ Tech Stack  

🔹 **Backend** – Java, Spring Boot, Spring MVC, Spring Security, Spring Data JPA  
🔹 **Frontend** – Thymeleaf, HTML, CSS, Bootstrap  
🔹 **Database** – MySQL/PostgreSQL  
🔹 **Security** – Spring Security, JWT  
🔹 **Other Tools** – Maven, Lombok, Postman  

## 📂 Project Structure  


studentdbms/
│── src/main/java/studentdbms
│   ├── controller/  # Handles HTTP requests  
│   ├── service/     # Business logic layer  
│   ├── repository/  # Data access layer (JPA Repositories)  
│   ├── model/       # Entity classes  
│   ├── config/      # Security & application configurations  
│── resources/templates/  # Thymeleaf templates  
│── resources/static/     # CSS, JS, images  
│── application.properties  # Database configurations  



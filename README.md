# Course Platform Database Design

## Project Overview
This project presents a **relational database design** for an online course / learning management platform.  
The database is designed to support core functionalities such as user management, course creation, student enrollment, lesson delivery, assignments, submissions, and progress tracking.

The schema is written using **DBML (Database Markup Language)** and is compatible with **dbdiagram.io**, allowing easy visualization and understanding of entity relationships.

---

## Purpose of the Project
The main goal of this project is to:
- Design a **normalized and scalable database structure**
- Clearly define relationships between users, courses, and learning activities
- Demonstrate understanding of **database modeling concepts** such as primary keys, foreign keys, and many-to-many relationships

---

## System Features Covered
The database design supports the following features:

- **User Management**
  - Users can have roles such as student, instructor, or admin

- **Course Management**
  - Instructors can create and manage courses
  - Courses contain multiple lessons

- **Enrollment System**
  - Students can enroll in multiple courses
  - Enrollment status is tracked

- **Lessons**
  - Courses are divided into ordered lessons
  - Each lesson contains learning content

- **Assignments & Submissions**
  - Courses can have assignments
  - Students submit assignments and receive grades

- **Progress Tracking**
  - Student progress is tracked at the lesson level

---

## Database Tables
The design includes the following main tables:

- `users`
- `courses`
- `lessons`
- `enrollments`
- `assignments`
- `submissions`
- `progress`

Each table uses appropriate primary keys and foreign keys to maintain data integrity.

---

## Tools Used
- **DBML (Database Markup Language)**
- **dbdiagram.io** for visualization
- Relational database design principles

---

## How to Use
1. Open https://dbdiagram.io
2. Create a new diagram
3. Paste the DBML code into the editor
4. View and export the database diagram as needed

---

## Conclusion
This database design provides a solid foundation for building an online course platform. It is scalable, easy to understand, and follows best practices in relational database modeling. The design can be further extended to include features such as payments, quizzes, certificates, and reviews.

---

## Author
**Avash Pradhan**

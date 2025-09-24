Student Records System (Database)

A relational database schema for managing student records, courses, enrollments, and grades.
This system is designed for educational institutions to track students, their course registrations, and academic performance.

Features

Students: Store student details (name, DOB, email, phone).

Courses: Maintain a catalog of available courses.

Enrollments: Manage many-to-many relationships between students and courses.

Grades: Assign grades to enrolled students.

🗄️ Database Schema
Entities & Relationships:

Students (1-to-Many with Enrollments)

Courses (1-to-Many with Enrollments)

Enrollments (junction table: Many-to-Many between Students and Courses)

Grades (1-to-1 with Enrollments)

SET UP INSTRUCTIONS

Clone this repository or copy the schema.sql file.

Open your MySQL terminal or client.

RUN:
mysql -u root -p < schema.sql


VERIFY DATABASE AND TABLES

SHOW DATABASES;
USE student_records_system;
SHOW TABLES;


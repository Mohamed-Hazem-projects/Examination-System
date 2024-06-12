#Examination System 
## Overview
This README provides an overview of the requirements and specifications for an examination system along with its associated SQL database. This system is designed to facilitate exams, manage exam-related data, and provide reporting capabilities for DEPI staff.

## System Requirements
Entity-Relationship Diagram (ERD)
Mapping of said ERD
Many reports , functionalities
The ERD illustrates the relationships between the key entities in the system, including Students, Instructors, Courses, Exams, Questions, Answers, and Departments.

## Database Dictionary
Above is a simplified database dictionary outlining the key tables and their respective columns:

## Stored Procedures
The system includes the following stored procedures for database management:

SELECT, INSERT, UPDATE, and DELETE procedures for any table.

Procedure for generating exams.

Procedure for recording and managing exam answers.

Procedure for correcting exams.

## Reporting
The system incorporates reporting features to assist Depi staff in managing and monitoring exams.

## Reports
Student Information by Department

Input: Department Number
Output: List of students in the specified department.
Grades by Student

Input: Student ID
Output: Student's grades in all courses.
Courses Taught by Instructor

Input: Instructor ID
Output: List of courses taught by the instructor and the number of students per course.
Topics by Course

Input: Course ID
Output: List of topics covered in the course.
Questions in an Exam

Input: Exam Number
Output: List of questions in the exam.
Student Exam Answers

Input: Exam Number, Student ID
Output: List of questions in the exam with the student's answers.

## Technology Stack
Database: SQL Server

## Implementation
The above requirements serve as the foundation for the development of the automated online examination system. It is crucial to ensure that the system is designed, implemented, and tested in accordance with these specifications to meet the needs of Depi staff and students effectively.

For detailed instructions on setting up and using the system, please refer to the system documentation or contact the system administrator.

For any questions or concerns, please contact Contact Information.

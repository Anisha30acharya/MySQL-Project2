# MySQL-Project2
 Online Course Enrollment System
 ---------------------------------
This SQL file creates and manages an Online Course Enrollment Database using standard SQL commands. The project covers database schema design, sample data population, and advanced SQL query techniques to simulate a student-course enrollment scenario.

🔧 Key Components:
1. Schema Creation
Database: OnlineCourseEnrollment
Tables:
Students: Stores student information such as ID, name, email, and join date.
Courses: Contains course details including course name, instructor, and credit count.
Enrollments: Tracks course enrollments with references to student and course IDs, along with enrollment date and grades.

2. Data Insertion
Includes sample data:
3 students (Alice, Bob, Charlie)
3 courses (Data Science 101, Python Programming, Data Structures)
4 enrollment records with different grades and enrollment dates to mimic realistic data.

3. SQL Queries
Retrieval and Filtering:
Students enrolled in a specific course (Data Science 101)
Students who have not enrolled in any course
Students who got an 'A' in all their courses
Students who enrolled in courses with “Python” in the name
Join Operations:
Display student names along with course and instructor details
Instructor of the most enrolled course
Students enrolled in more than one course by the same instructor
Grouping and Aggregation:
Number of courses each student has passed (Grades A/B/C)
Count of student enrollments per month in 2024
Courses with enrollments above the average
Nested Queries:
Courses exceeding average enrollments (using subqueries)
Students with consistent 'A' grades across all enrolled courses

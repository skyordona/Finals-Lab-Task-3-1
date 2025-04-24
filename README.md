# [Midterm Lab Task 3-1 - Using MYSQL Clause](https://github.com/user-attachments/files/19890889/Finals.Lab.Task.3.1.-.Ordona.docx)

## Step by Step Process
- **Step 1: Create the Database**
  - Open your MySQL environment (like MySQL Workbench or phpMyAdmin).
  - Create a new database by typing the command:
    - `CREATE DATABASE online_courseDB;`
  - This command sets up the main storage space for your online course data.

- **Step 2: Select the Database**
  - Choose or switch to the newly created database to start working in it:
    - `USE online_courseDB;`
  - This ensures all tables and queries will be applied to the correct database.

- **Step 3: Load Initial Data**
  - Download the `onlineCourse.l` file provided in the instructions.
  - Run or import this file into the MySQL environment.
    - It will automatically:
      - Create a table called `courses`.
      - Add 20 course records into the table.
  - Make sure the table has the following fields:
    - `id`: auto-incremented primary key.
    - `course_name`: VARCHAR, not null.
    - `category`: VARCHAR, not null.
    - `enrollment_limit`: INTEGER, not null.
    - `students_enrolled`: INTEGER, not null.

- **Step 4: Perform SQL Tasks in Order**

  - **Task 1: List Courses Below Capacity**
    - Find and display all courses where the number of enrolled students is less than the enrollment limit.
    - SQL Concept: `SELECT` with `WHERE` condition.

  - **Task 2: Group by Category**
    - Group the courses by their category and show the total number of enrolled students per category.
    - SQL Concepts: `GROUP BY` and `SUM()` function.

  - **Task 3: Show Fully Enrolled Courses**
    - Display courses where the number of students enrolled equals the enrollment limit.
    - SQL Concept: Equality condition in `WHERE`.

  - **Task 4: Total Students in All Courses**
    - Calculate and display the total number of students enrolled across all 20 courses.
    - SQL Concept: Aggregation using `SUM()`.

  - **Task 5: Sort Courses by Enrollment**
    - Display all courses ordered by the number of students enrolled, from lowest to highest.
    - SQL Concept: `ORDER BY` with ascending sort.

- **Final Step: Review Results**
  - Check that each query produces the expected output.
  - Verify correct field names and data consistency.

# Screenshots
## Query Statements
### 1. Task 1
- ![Image](https://github.com/user-attachments/assets/30cda5c9-9b7d-4b14-8a30-41fd9d4f1109))
### 2. Task 2
- ![Image](https://github.com/user-attachments/assets/8d6d5f53-e915-4f09-815f-7b9d9153abe2)
### 3. Task 3
- ![Image](https://github.com/user-attachments/assets/1a5505f4-b815-4278-ba31-cfec3a3fd936)
### 4. Task 4
- ![Image](https://github.com/user-attachments/assets/9545a9fa-906b-478f-8b13-ceb4fd2b3320)
### 5. Task 5
- ![Image](https://github.com/user-attachments/assets/7acadcaa-55e7-4134-ba4d-7429dfa171e6)

## Table Structure
1. Task 1
- ![Image](https://github.com/user-attachments/assets/e18f681b-716b-46d7-a615-9b7b2c9b91b6)
2. Task 2
- ![Image](https://github.com/user-attachments/assets/547d0798-18f3-4746-a49d-8b0ec98dce41)
3. Task 3 
- ![Image](https://github.com/user-attachments/assets/49d9f67d-16e7-49d3-a0fe-3abcef8b4332)
4. Task 4
- ![Image](https://github.com/user-attachments/assets/f8fb9c00-8b15-483b-bd9d-93f87fd3b3eb)
5. Task 5
- ![Image](https://github.com/user-attachments/assets/6b3bed9e-d1e3-4cbb-895d-ffc23a26c121)

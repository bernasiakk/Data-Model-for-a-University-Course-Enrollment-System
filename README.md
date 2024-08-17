### **Challenge: University Course Enrollment System**

**Scenario:**
You are tasked with designing a database for a university course enrollment system. The system should allow students to enroll in courses, and the university needs to track the enrollment status, course details, and instructor assignments. The university also offers different programs, and each student is enrolled in a specific program.

**Requirements:**

1. **Students:**
    - Each student has a unique ID, name, email, date of birth, and the program they are enrolled in.
    - A student can be enrolled in one program but can take multiple courses.
2. **Programs:**
    - Each program has a unique ID, name, description, and duration.
    - A program consists of multiple courses, but each course can belong to multiple programs.
3. **Courses:**
    - Each course has a unique ID, name, description, and the number of credits.
    - A course can have multiple instructors, but each instructor can teach multiple courses.
4. **Instructors:**
    - Each instructor has a unique ID, name, email, and department.
    - An instructor can teach multiple courses.
5. **Enrollments:**
    - The system should track which students are enrolled in which courses.
    - Each enrollment has a status (e.g., enrolled, completed, dropped).

**Objectives:**

1. **Design an ERD (Entity-Relationship Diagram):**
    - Identify entities, attributes, and relationships.
    - Define primary keys and foreign keys.
2. **Create a relational schema:**
    - Translate the ERD into a relational schema.
    - Specify the tables, columns, and data types.

**Answer:**
1. See [answer.md](answer.md)
# lastflaskproject
Objective

You will create a web application using Flask to manage a school's basic operations. The app will include session handling for user authentication and CRUD (Create, Read, Update, Delete) operations for the following models:

    Course - Represents the courses offered by the school.
    Teacher - Represents the teachers who conduct the courses.
    Session - Represents the sessions of each course, including the teacher and time.

Functional Requirements
Authentication

    Users must log in to access the application.
    Implement session handling to manage user sessions.
    Add a simple logout functionality.

Course Management

    CRUD operations for courses.
    A course has the following attributes:
        id, name, description

Teacher Management

    CRUD operations for teachers.
    A teacher has the following attributes:
        id, name, email, specialization
        
Session Management

    CRUD operations for sessions.
    A session belongs to a course and is conducted by a teacher.
    A session has the following attributes:
        id, course_id, teacher_id, date, duration

User Interface

    Create a dashboard where authenticated users can:
        View a list of all courses, teachers, and sessions.
        Navigate to forms to add new courses, teachers, or sessions.
        Edit or delete existing records.

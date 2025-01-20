README for MyUniversity Class-Based Program
Overview
This program implements a university management system using Python. It uses the MyUniversity class to manage students and courses, allowing operations like registration, listing, and checking enrollment through a menu-driven interface.

Features
Student Management:

Add a student with a unique ID and name.
Retrieve a list of courses a student is registered for.
Course Management:

Add a course with a unique course number and title.
Retrieve a list of students enrolled in a course.
Student-Course Interaction:

Register a student for a course.
Check if a student is registered for a specific course.
Remove a student's registration from a course.
Statistics:

Get the total number of students registered for a course.
List students registered for at least one course.
List courses with more than a specified number of students.
Class: MyUniversity
Attributes
students: A dictionary storing student details in the format {student_id: (student_name, [course_no])}.
courses: A dictionary storing course details in the format {course_no: (course_title, [student_ids])}.
Methods
1. add_student(student_id, student_name)
Adds a new student to the system.

2. add_course(course_no, course_title)
Adds a new course to the system.

3. register_student_for_course(student_id, course_no)
Registers a student for a specific course if both exist and the student is not already registered.

4. get_the_courses_from_student(student_id)
Lists all courses a student is registered for.

5. get_the_students_from_course(course_id)
Lists all students enrolled in a specific course.

6. get_total_students_in_the_course(course_id)
Displays the total number of students registered in a course.

7. get_students_registered_for_atleast_one_course()
Lists all students who are registered for at least one course.

8. get_course_of_x_number_of_student_registered()
Lists courses with more than a user-specified number of registered students.

9. has_student_registered_for_course(student_id, course_no)
Checks if a specific student is registered for a specific course.

10. remove_student_name_for_the_course(student_id, course_no)
Removes a student’s registration from a specific course.

Menu-Driven Interface
The main() function provides an interactive menu for users to:

Add students or courses.
Register students for courses.
Retrieve and display student and course data.
Perform additional operations like checking enrollment, removing students from courses, and viewing statistics.
Exit the program.

# Student-Management-System-using-Nested-Lists-and-Nested-Tuples-as-Sample-Data
Here's a simple project that demonstrates the use of nested lists and nested tuples in Python. The project is a Student Management System, where we store student details such as their name, subjects, and marks in a nested list and nested tuple format.

Project: Student Management System
Objective:
Store student details in a nested list, where each student has a list of subjects, and each subject has a tuple of marks.
Perform basic operations like displaying student data, calculating average marks, and printing a report.

Data Structure:
Nested List: Each student is represented by a list containing:
The student's name (a string).
A list of subjects (a list of strings).
A tuple of marks corresponding to those subjects (a tuple of integers).
For example:
python
Copy
["Alice", ["Math", "Science", "History"], (85, 90, 88)]
This means Alice is enrolled in Math, Science, and History, and her marks are 85, 90, and 88, respectively.
Functions:

display_student_details: Iterates through the students list and displays each student's name, subjects, and marks.
calculate_average_marks: Takes a student's name as input, finds the student in the list, and calculates the average of their marks.
generate_report_card: Displays a report card for each student, including their total marks, marks per subject, and average marks.
Main Menu:

A menu-driven interface allows users to choose between viewing all student details, calculating the average marks of a specific student, or generating report cards for all students.

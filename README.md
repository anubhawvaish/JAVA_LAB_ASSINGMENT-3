📘 Student Management System – Exception Handling & Multithreading (Java)

This project enhances the Student Management System by adding exception handling, custom exceptions, multithreading, and wrapper classes. It ensures safe user input, prevents crashes, and provides a responsive experience using a loading simulation thread.

🚀 Features

✔ Custom Exception: StudentNotFoundException

✔ Input validation using try–catch–finally

✔ Loader thread using Runnable + Thread.sleep()

✔ Wrapper classes (Integer, Double) with autoboxing

✔ Prevents invalid marks and empty fields

✔ Prevents duplicate roll numbers

✔ CRUD actions: Add, Search, View All

✔ Fully menu-driven system

✔ Works perfectly in online compilers

🏗 Class Overview

Student
Fields: rollNo, name, email, course, marks, grade

Uses wrapper classes (Integer, Double)

Auto-calculates grade

Method: display()

StudentNotFoundException (Custom Exception)
Thrown when a student is not found during search.

Loader (implements Runnable)
Simulates a loading animation using multithreading

Runs in a separate thread to improve responsiveness

RecordActions (Interface)
Methods:

addStudent()

searchStudent()

viewAllStudents()

StudentManager (implements RecordActions)
Stores student records in a HashMap<Integer, Student>

Handles:

Adding students

Searching students

Viewing all students

Input validation

Exception handling

Multithreading for loading animation

RecordSystem3 (Main Class)
Runs the main menu

Connects all components

Handles program execution

🧠 Concepts Implemented ✔ Exception Handling

try–catch–finally

Input validation

Custom exception (StudentNotFoundException)

✔ Multithreading

Loader animation using Thread + Runnable

Thread.sleep() to simulate processing delay

✔ Wrapper Classes

Integer, Double used for input handling

Autoboxing & unboxing shown in program

📌 Sample Output Enter Roll No (Integer): 102 Enter Name: Karan Enter Email: karan@mail.com Enter Course: BCA Enter Marks: 77.5 Loading..... Student added successfully! Operation completed.

===== Student Management Menu =====

Add Student
Search Student
View All Students
Exit Enter choice: 2 Enter Roll No to search: 102
Roll No: 102 Name: Karan Email: karan@mail.com Course: BCA Marks: 77.5 Grade: B
▶️ How to Run Online Compiler

Open any online Java compiler

Paste the entire code into one file

Make sure the main class is:

public class RecordSystem3

Run the program

🎯 Learning Outcomes

After completing this assignment, you will understand:

How to design custom exceptions

How to handle runtime errors safely

How to create and run threads in Java

How wrapper classes & autoboxing work

How to design a modular Java application

👨‍💻 Author

Your Name Aryaveer Singh 2401010273 B.Tech CSE K.R. Mangalam University

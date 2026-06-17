# Student Data Collector (Collection Manipulator)

## Project Description

The **Student Data Collector** is a Python console-based application that stores and manages student records using lists and dictionaries. It allows users to add, display, update, delete student records, and view the subjects offered.

## Features

* Add new student records
* Display all student records
* Update student information
* Delete student records
* Display unique subjects offered
* Exit the application

## Concepts Used

* Lists
* Dictionaries
* `while` loop
* `match-case`
* `for` loop
* `if-else`
* User input
* CRUD Operations (Create, Read, Update, Delete)

## Input

The program accepts the following inputs:

* Menu choice (1–6)
* Student ID
* Student Name
* Student Age
* Student Grade
* Date of Birth (DD-MM-YYYY)
* Student Subject(s)

## Output

The program displays:

* Confirmation message after adding a student.
* List of all student records.
* Success message after updating a student.
* Success message after deleting a student.
* List of unique subjects offered.
* Exit message when the program ends.

## Sample Input

```
Enter your choice: 1
Enter student id: 101
Enter student name: Niral
Enter student age: 19
Enter student grade: A+
Enter date of birth: 15-01-2007
Enter student's subject: OS, JAVA
```

## Sample Output

```
Your record has successfully added.
```

### Display Records

```
Student ID: 101
Student Name: Niral
Student Age: 19
Student Grade: A+
Date of Birth: 15-01-2007
Subject: OS, JAVA
```

### Update Output

```
Student record updated successfully.
```

### Delete Output

```
Student record deleted successfully.
```

### Subjects Offered

```
Subjects Offered:
OS, JAVA
Python, .NET
```

### Exit Output

```
Thank You!! For using Collection Manipulator.
```

## Conclusion

This project demonstrates the use of Python collections to perform basic student record management through a simple menu-driven application. It helps in understanding CRUD operations, lists, dictionaries, loops, and conditional statements.

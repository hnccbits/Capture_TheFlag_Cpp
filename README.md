# Student Management System CPP

![ctf.jpeg](Student%20Management%20System%20CPP%2016bb04b52d0947769c43cb66249e8b44/ctf.jpeg)

## **Overview**

This project is a program for managing student records. It allows the user to create, view, search, update, and delete student records. The program uses an array of structures to store the student records.

## **Features**

The program allows an admin to manage a table of student data, with a maximum of 20 students that can be stored. The following functions are available for the admin to manage the student records:

1. **`Build()`**: This function helps in initializing student details, where the admin is first asked for the number of students to enter, and then the admin can enter the data of each student respectively.
2. **`Insert()`**: This function helps in inserting a new student detail into the current table.
3. **`DeleteRecord()`**: This works with the help of another function, which is **`DeleteIndex()`**. First, **`DeleteRecord()`** takes the input of the student ID from the admin and searches for the student in the record. If the student is found, then it passes the index of the student to **`DeleteIndex()`** function for deleting the student record.
4. **`SearchRecord()`**: This function searches for the details of a student in the record using the student ID taken as an input from the admin. If the student is found, then it displays the record of the student on the screen.
5. **`DisplayRecord()`**: This function helps in displaying the details of all students in the record.
6. **`UpdateRecord()`**: This function searches for a student in the record using the student ID taken as an input from the admin. If the student is found, then it updates the new details of the student that are input by the admin.
7. **`ShowMenu()`**: It displays all available options of the project for the admin. From here, the admin can navigate to all functions. This is one of the main functions of the project. When the user selects an option from the menu, the program calls a function that performs the selected operation. Each function performs the required operation on the array of structures.

## **Installation**

### **Prerequisites**

- Install a C++ compiler such as GCC, Clang, or Microsoft Visual C++ on your computer.
- A text editor or an IDE such as  Visual Studio Code, or Sublime.

### **Setup**

1. Fork and clone the repository to the local computer.
2. Open the project directory in a text editor or an IDE.
3. To run the program:
    - Navigate to the project directory in the terminal or command prompt.
    - Run the command g++ **`StudentManagement.cpp`**.
4. To run the program in an IDE, open project in IDE and run the **`StudentManagement.cpp`** file.

## **Bugs**

The following bugs are present in the program:

1. The program allows for duplicate student IDs to be stored.
2. The search function has a bug that incorrectly identifies and displays the student record that matches the entered student ID.
3. The update function is not correctly updating the student record with new details entered by the admin.
4. The student records are not displayed in proper order when using the display function.
5. The program terminates when the display function finishes displaying the records, instead of returning to the main menu.
6. There is a bug in the delete function that is causing student records to not be deleted properly.

## Rules :

1. Each team can participate in only one programming language.
2. To participate, you must fork this repository, make the necessary changes to the file(s), and then create a pull request (PR) on the main branch with the correct code.
3. Teams will be ranked based on the time they take to create the PR and the accuracy of their code.
4. For time-based ranking, only the time taken for the last commit will be considered. Multiple commits can be made in a single PR.
5. Any commit made after 12 pm will not be considered for any team.
6. To be ranked based on code, your submitted code must solve all the bugs listed in the project description.
7. You are allowed to explain your changes using comments.
8. We hope these rules are clear and easy to follow. Good luck with the contest!

## **Task**

The task is to resolve all the identified bugs within the student management system, and to create a pull request (PR) with the proposed fixes.
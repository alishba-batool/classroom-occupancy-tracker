CLASSROOM OCCUPANCY MANAGEMENT SYSTEM

DESCRIPTION:
A complete, menu-driven C++ console application for managing classrooms, teachers, and students within a building. Developed as an academic Object-Oriented Programming (OOP) project, it provides functionalities for classroom allocations, teacher assignments, student management, room occupancy reporting, and data saving — all through an interactive command-line interface.

PROJECT MOTIVATION:
This project aims to:

Apply core object-oriented principles: Inheritance, Polymorphism, Encapsulation, Composition.
Practice dynamic memory management in C++.
Simulate a real-world classroom management system.
Build a simple, interactive console application for academic use.
TECHNOLOGIES USED:
Programming Language : C++
Compiler : GCC / g++
User Interface : Console-based (command-line)


SYSTEM DESIGN OVERVIEW:
CLASSES AND RELATIONSHIPS:
Person (Abstract Base Class)

Attributes: name, id
Pure virtual function: displayInfo()
Student (inherits from Person)

Attribute: program
Implements displayInfo()
Teacher (inherits from Person)

Attribute: subject
Implements displayInfo()
Classroom

Attributes: roomNumber, capacity
Pointer to Teacher
Array of Students
Logs for all activities
Functions for adding/removing students, assigning teachers, transferring students, displaying details, saving data.
Building

Attribute: name
Array of Classrooms
Functions for adding classrooms, searching, transfers, displaying summaries, and saving data.
FEATURE HIGHLIGHTS:
- Add Classrooms with capacity limit
- Assign Teachers to specific classrooms
- Add/Remove Students with duplicate ID checks
- Transfer Students between classrooms
- Search for a Student or Teacher by ID (with room info)
- Display classroom details: occupancy, students, teacher, logs
- Show Building Summary: total students, capacity, occupancy %
- Save current data (formatted console output)
- Simple, menu-driven console interface


MENU OPTIONS:
Add Classroom
Assign Teacher
Add Student
Remove Student
Show All Classrooms
Search Student by ID
Search Teacher by ID
Transfer Student
Show Building Summary
Save Data
Exit
EXAMPLE OPERATIONS:
Add Classroom: → Enter room number and capacity.

Assign Teacher: → Enter room number, teacher’s name, ID, subject.

Add Student: → Enter room number, student’s name, ID, program.

Remove Student: → Enter room number and student ID.

Transfer Student: → Enter student ID, source room number, destination room number.

Show Summary: → Displays total students, total capacity, occupancy %.

Save Data: → Outputs all room data in structured format.

DATA SAVE FORMAT EXAMPLE:
Room:101|Capacity:40|Students:12,Ali;14,Sana;|Teacher:22,Mr. Kamran

OCCUPANCY STATUS EXAMPLE:
Classroom 101 Capacity: 40, Occupied: 20, S

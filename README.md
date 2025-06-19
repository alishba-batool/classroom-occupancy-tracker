Classroom Occupancy Tracker

Project Description

The Classroom Occupancy Tracker is a C++ application designed to manage and monitor classroom occupancy within an academic building. It provides a comprehensive system to track students, teachers, and classroom assignments, offering functionalities such as adding classrooms, assigning teachers, managing student enrollment, transferring students between rooms, and generating occupancy reports. The system uses object-oriented programming principles to model entities like Person, Student, Teacher, Classroom, and Building, ensuring modularity and extensibility.

Key Features

Classroom Management: Add classrooms with specified room numbers and capacities, up to a maximum of 50 rooms.

Teacher Assignment: Assign or replace teachers to classrooms, with each teacher having a name, ID, and subject.

Student Management: Add or remove students (up to 100 per classroom) with details like name, ID, and program, ensuring no duplicate student IDs.

Occupancy Tracking: Display real-time occupancy status with a visual bar representation and percentage for each classroom.

Student Transfer: Transfer students between classrooms while respecting capacity constraints.

Search Functionality: Search for students or teachers by ID across all classrooms.

Logging: Maintain a log of actions (e.g., adding/removing students, assigning teachers) for each classroom, with a maximum of 500 logs per room.

Data Persistence: Save classroom data in a structured format for easy retrieval.

User Interface: Interactive console-based menu for seamless user interaction.

Technical Details

Language: C++ (using standard libraries like <iostream>, <string>, <limits>)

Design: Object-oriented with inheritance (Person as a base class for Student and Teacher) and composition (Classroom and Building classes).

Data Structures: Arrays for storing students, logs, and classrooms, with defined limits for scalability and memory management.

Error Handling: Input validation for integers and strings, preventing invalid room capacities, duplicate IDs, or full classrooms.

Memory Management: Proper use of dynamic memory for teacher assignments with cleanup in destructors to prevent memory leaks.

Use Cases

This application is ideal for educational institutions to efficiently manage classroom assignments and track occupancy. It can be extended to integrate with a database or GUI for enhanced functionality.

How to Run

Compile the class-occupancy-tracker.cpp file using a C++ compiler (e.g., g++).

Run the executable to access the interactive menu.

Follow the menu prompts to manage classrooms, teachers, and students.

Potential Enhancements

Integration with a file-based or database storage system for persistent data.

Graphical user interface (GUI) for a more user-friendly experience.

Support for multiple buildings or campuses.

Advanced analytics for occupancy trends and teacher workload.

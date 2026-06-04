# University Management System

A C++ Object-Oriented Programming project that simulates a basic university management system.  
It manages students, professors, courses, departments, classrooms, schedules, grades, and enrollments.

## Features

- Manage person, student, and professor details
- Support undergraduate and graduate students
- Support assistant, associate, and full professors
- Course enrollment and student drop functionality
- GradeBook with average, highest marks, and failing students
- Department and university management
- Classroom scheduling with time-slot conflict checking
- Custom exception handling
- Error logging using file handling
- Polymorphism using base class pointers

## OOP Concepts Used

- Classes and objects
- Inheritance
- Polymorphism
- Function overriding
- Encapsulation
- Exception handling
- File handling
- STL containers like `vector` and `map`

## Class Hierarchy

```text
Person
├── Student
│   ├── UndergraduateStudent
│   └── GraduateStudent
└── Professor
    ├── AssistantProfessor
    ├── AssociateProfessor
    └── FullProfessor
```

## Main Classes

- `Person`
- `Student`
- `Professor`
- `Course`
- `Department`
- `University`
- `GradeBook`
- `EnrollmentManager`
- `Classroom`
- `Schedule`

## How to Run

Save the code as:

```bash
main.cpp
```

Compile:

```bash
g++ main.cpp -o university_system
```

Run:

```bash
./university_system
```

On Windows:

```bash
university_system.exe
```

## Error Log

Enrollment-related errors are saved in:

```text
university_system_error.log
```

## Future Improvements

- Add menu-driven interface
- Add database/file storage
- Improve date validation
- Add search features
- Add attendance and fee modules

## Author

C++ OOP University Management System project.

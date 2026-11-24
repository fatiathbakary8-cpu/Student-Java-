# Student-Java-
Student Management System using Java

# Student Management System

## Description
This project is a simple Student Management System developed using Java.

## Class Diagram

```mermaid
classDiagram
    class Student {
        -int studentId
        -String name
        -int age
        -String department
        -double GPA
        +Student(int id, String n, int a, String d, double g)
        +displayInfo() void
    }

    class Main {
        +main(String[] args) void
    }

    Main ..> Student : uses
```

## Programming Language
Java

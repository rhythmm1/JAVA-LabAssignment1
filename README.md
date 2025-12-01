# Student Record Management System

## Overview
A Java-based console application for managing student records with features including adding students, displaying all records, and automatic grade calculation based on marks.

## Features
- **Object-Oriented Design**: Implements inheritance with `Person` base class and `Student` derived class
- **Dynamic Data Storage**: Uses ArrayList for flexible student record management
- **Automatic Grade Calculation**: Assigns grades A-D based on marks criteria
- **Interactive Menu System**: User-friendly console interface
- **Data Validation**: Ensures proper input handling

## System Requirements
- **Java Development Kit (JDK)**: Version 8 or higher
- **Operating System**: Windows, macOS, or Linux
- **Memory**: Minimum 512 MB RAM

## How to Run the Program

### Method 1: Using Command Line

#### Step 1: Compile the Code
```bash
javac Main.java
```

#### Step 2: Run the Program
```bash
java Main
```

### Method 2: Using an IDE (IntelliJ IDEA, Eclipse, NetBeans)

1. Create a new Java project
2. Copy the `Main.java` file into the `src` folder
3. Right-click on `Main.java` and select "Run"

### Method 3: Using Online Compiler
1. Visit [GDB](https://onlinegdb.com/CSXu_wWUbH) or similar Java online compiler
2. Copy and paste the entire code
3. Click "Execute" or "Run"

## Usage Guide

### Menu Options

When you run the program, you'll see:

```
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
```

### 1. Add Student
- Enter roll number (integer)
- Enter student name (string)
- Enter course name (string)
- Enter marks (decimal number, 0-100)
- Grade is automatically calculated

### 2. Display All Students
- Shows all student records with their details
- Displays: Roll No, Name, Course, Marks, and Grade

### 3. Exit
- Closes the application

## Grade Calculation Criteria

| Marks Range | Grade |
|-------------|-------|
| 90 - 100    | A     |
| 75 - 89     | B     |
| 60 - 74     | C     |
| Below 60    | D     |

## Sample Run

```
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 1
Enter Roll No: 298
Enter Name: Abhinav Adarsh
Enter Course: Computer Science
Enter Marks: 85.5

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 2
Roll No: 298
Name: Abhinav Adarsh
Course: Computer Science
Marks: 85.5
Grade: B
---------------------------
```

## Performance Metrics Coverage

### Core Design and Implementation (3 Marks)
- ✅ Inheritance: `Student` extends `Person` class
- ✅ Proper class structure with constructors
- ✅ Object-oriented principles applied

### Array Handling and Data Validation (2 Marks)
- ✅ ArrayList for dynamic data storage
- ✅ Input validation through Scanner
- ✅ Proper data type handling

### Methods Implementation (2 Marks)
- ✅ `inputDetails()`: Captures student information
- ✅ `calculateGrade()`: Automatic grade assignment
- ✅ `displayDetails()`: Formatted output display

### Menu System and User Interaction (2 Marks)
- ✅ Interactive menu with multiple options
- ✅ Loop-based menu for continuous operation
- ✅ Exit option for clean termination

### Code Quality and Documentation (1 Mark)
- ✅ Clean, readable code structure
- ✅ Meaningful variable and method names
- ✅ Proper indentation and formatting

## Troubleshooting

### Common Issues

**Issue**: "class Main is public, should be declared in a file named Main.java"
- **Solution**: Ensure the file is named exactly `Main.java`

**Issue**: Program crashes on input
- **Solution**: Enter data in the correct format (integers for roll no, decimal for marks)

**Issue**: Scanner not taking string input
- **Solution**: Code includes `sc.nextLine()` after `nextInt()` to handle newline

## Code Structure

```
Main.java
├── Person (Base Class)
│   └── String name
├── Student (Derived Class)
│   ├── int rollNo
│   ├── String course
│   ├── double marks
│   ├── char grade
│   ├── inputDetails()
│   ├── calculateGrade()
│   └── displayDetails()
└── Main (Entry Point)
    └── main() method with menu system
```


## Author Information
- **Program**: Student Record Management System
- **Language**: Java
- **Version**: 1.0

- **Author**: Rhythm Singhal

**Note**: This program runs entirely in the console. Ensure your terminal/command prompt is properly configured to display output.# Student-Record-Menu

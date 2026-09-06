# Employee Data Management System

A Python command-line application for managing employee information using file handling and persistent text-file storage.

## 📌 Project Overview

The Employee Data Management System allows users to store, view, search, and analyze employee performance data.

Unlike a basic in-memory Python program, this project stores employee information in a text file, allowing the data to persist even after the program is closed.

The project was developed to practice Python fundamentals, file handling, functions, dictionaries, loops, conditions, and modular program design.

## 🚀 Features

* View all employees
* Add new employees
* Search employees by name
* Calculate average employee score
* Generate employee performance reports
* Store employee data permanently in a text file
* Interactive command-line menu

## 🛠️ Technologies Used

* Python 3
* File Handling
* Lists
* Dictionaries
* Functions
* Loops
* Conditional Statements
* String Manipulation
* Command-Line Interface (CLI)

## 📋 Application Menu

```text
===== EMPLOYEE DATA MANAGEMENT =====

1. View Employees
2. Add Employee
3. Search Employee
4. Calculate Average Score
5. Generate Performance Report
6. Exit
```

## 📂 Data Storage

Employee information is stored in `Employees.txt`.

Each employee is stored using the following format:

```text
Name,Department,Score
```

Example:

```text
Rahul,Testing,85
Priya,Software,92
Arun,Testing,67
```

The program reads the file and converts the stored data into Python dictionaries for processing.

## 🧠 Concepts Practiced

### File Handling

The project uses Python's file handling capabilities to:

* Read employee data
* Append new employee records
* Process stored information

Example:

```python
with open("Employees.txt", "a") as file:
    file.write(...)
```

### Data Conversion

Data read from the text file initially comes in string format. Employee scores are converted into integers for calculations.

```python
int(dic[2])
```

### Functions

The application is divided into multiple functions, with each function responsible for a specific task.

Examples:

```text
add_employees()
load_employees()
save_employee()
view_employees()
search_employee()
calculate_average()
find_grade()
performance_report()
```

### Performance Classification

Employee scores are classified as:

|         Score | Performance |
| ------------: | ----------- |
|        90–100 | Excellent   |
|         75–89 | Good        |
|         60–74 | Average     |
|          0–59 | Poor        |
| Outside 0–100 | Invalid     |

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/employee-data-management-system.git
```

### 2. Navigate to the project

```bash
cd employee-data-management-system
```

### 3. Run the program

```bash
python main.py
```

## 💻 Example

```text
===== EMPLOYEE DATA MANAGEMENT =====

1. View Employees
2. Add Employee
3. Search Employee
4. Calculate Average Score
5. Generate Performance Report
6. Exit

Enter your choice: 1

The Employees are:
Rahul,Testing,85
Priya,Software,92
Arun,Testing,67
```

## 📈 Future Improvements

The project can be extended with:

* Input validation
* Exception handling
* Employee ID support
* Update employee details
* Delete employee records
* Department-wise analysis
* Sorting employees by score
* CSV or JSON data storage
* Better formatted reports
* Unit testing
* Object-Oriented Programming
* Database integration

## 🎯 Learning Objective

This project was built as part of a structured Python learning journey to strengthen programming fundamentals and develop practical, GitHub-ready projects.

The main goal was to understand how Python programs can work with persistent data instead of relying only on data stored in memory.

## 👨‍💻 Author

**Kadam Lokeshwar Rao**

B.Tech – Electrical and Electronics Engineering

Interested in Python, Software Engineering, AI/ML and Generative AI.

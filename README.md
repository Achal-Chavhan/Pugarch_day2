# Pugarch_day2

Student Management System & Data Analysis

A simple Python-based Student Management System that stores student records in a CSV file and provides different operations for managing and analyzing student data.

The project is built using Python's built-in csv module and is designed as a beginner-friendly command-line application.

Features
Student Management

The system provides the following operations:

Add a new student
Update existing student details
Delete a student
Search students by ID or name
Filter students by:
Department
Age
Minimum marks
Sort students by:
Name
Age
Marks
Display all student records

The main menu provides these operations through a simple command-line interface.

Data Analysis

The project also includes a separate data analysis module that can generate:

Total record count
Missing value count
Duplicate student IDs
Average marks
Minimum marks
Maximum marks
Department-wise statistics

The analysis menu provides options for each of these operations.

Technologies Used
Python 3
CSV
Command Line Interface (CLI)
Python csv module
Python collections.Counter

No external Python libraries are required.

Project Structure
Student-Management-System/
│
├── main.py
├── student_manager.py
├── analysis.py
├── student_data.csv
└── README.md

Run

cd management-system
python main.py


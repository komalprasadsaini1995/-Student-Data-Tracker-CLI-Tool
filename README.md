# -Student-Data-Tracker-CLI-Tool
Overview
A Python-based command-line application for managing student records. This tool allows users to add, view, analyze, and export student data with marks in three subjects.

Features
Add Student Records: Store student names, roll numbers, and marks in 3 subjects

View Records: Display all student data in a formatted table

Calculate Averages: Compute and display average marks for each student

Export Data: Save records to a CSV file for external use

Input Validation: Ensures data integrity with comprehensive validation

User-Friendly Interface: Simple menu-driven interaction

Requirements
Python 3.x

No additional libraries required (uses built-in modules)

Installation
Clone the repository or download the .ipynb file

Ensure Python 3 is installed on your system

No additional installation steps required

Usage
Run the program in a Python environment (Jupyter Notebook or as a standalone script):

bash
python student_data_tracker.py
Or run the cells in the Jupyter Notebook.

Menu Options
Add Student Record: Enter student details including name, roll number, and marks for 3 subjects

Display All Records: View all stored student data in a tabular format

Calculate Average Marks: See the average marks for each student

Save Records to CSV: Export all data to a CSV file

Exit: Quit the program

Data Structure
Each student record contains:

Name (string)

Roll Number (string)

Marks (list of 3 float values)

All records are stored in memory as a list of dictionaries.

Error Handling
The program includes comprehensive error handling for:

Invalid menu choices

Empty name/roll number fields

Marks outside the 0-100 range

File saving errors

# Employee Management System
This Employee Management System is a simple command-line interface (CLI) application built in JavaScript to manage employees in an office. 
It allows users to add new employees, check employee details, and fire employees.

## Table of Contents

Features
Getting Started
Usage
Classes
License

## Features
Add New Employee: Users can add new employees to the office by providing necessary details such as name, email, age, role, and salary.

Check Employee: Users can check the details of a specific employee by entering their ID. The system provides information such as email, work mood, salary (for managers), and health rate (for normal employees).

Fire Employee: Users can remove an employee from the system by providing their ID.

## Getting Started
To get started with the Employee Management System, follow these steps:

Clone the repository to your local machine.

git clone https://github.com/IngyEl-Sakhawy/javaScriptLab5.git


## Usage
Enter the office name when prompted.

Choose from the menu options:

Press 1 to add a new employee.

Press 2 to check employee details.

Press 3 to fire an employee.

Press 4 to quit the application.

Follow the prompts to input necessary details for each operation.

## Classes
Person
Represents a general person with attributes such as ID, email, work mood, salary, and health rate.
Provides methods for sleeping, eating, buying items, and working.
Employee
Extends the Person class and represents an employee in the office.
Office
Manages a collection of employees.
Provides methods to get all employees, get details of a specific employee, hire a new employee, and fire an employee.


##License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for educational and non-commercial purposes.

Enjoy managing your employees with this Employee Management System!

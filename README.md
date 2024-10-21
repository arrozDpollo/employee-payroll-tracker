# Employee Payroll Tracker

## Overview
The **Employee Payroll Tracker** is a simple web application that allows you to track employee details, including first name, last name, and salary. The application lets you add multiple employees, displays them in a table, calculates the average salary, and selects a random employee.

## Features
- Add employees to the roster (including first name, last name, and salary).
- Display the employees in a table.
- Calculate and display the average salary of the employees.
- Select and display a random employee.
- Sort employees by last name in alphabetical order.

## Technologies Used
- **HTML5** for the structure of the webpage.
- **CSS3** for basic styling.
- **JavaScript** for managing employee data, updating the UI, and handling user input.

## Usage Instructions
1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Click on the "Add Employees" button to add employee details. You can add multiple employees.
4. After adding employees, the following actions will happen:
   - Employees will be displayed in the table.
   - The average salary of all employees will be calculated and shown via an alert.
   - A random employee will be selected and displayed via an alert.

## File Structure



## Functions Overview
- **`collectEmployees()`**: Prompts the user to enter employee details (first name, last name, salary) and returns an array of employee objects.
- **`displayAverageSalary(employeesArray)`**: Calculates the average salary of the employees in the array and displays it in an alert.
- **`getRandomEmployee(employeesArray)`**: Selects a random employee from the list and displays their details in an alert.
- **`displayEmployees(employeesArray)`**: Populates the employee table with the employee data and sorts them by last name.

## Future Improvements
- Add form inputs for employee data collection instead of using prompts.
- Add input validation for salary (to ensure only numerical values are entered).
- Improve UI styling for better visual appeal.
- Add options to edit or delete employee records.

## License
This project is open-source and freely available for personal or educational use.


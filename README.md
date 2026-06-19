# EMPLOYEE_REG_PAGE

A simple web-based Employee Registration System built using HTML, CSS, and JavaScript.

The application allows users to register employees by entering their details and validates all inputs before completing the registration process.

## Features

- Employee registration form
- First name and last name validation
- Age and experience validation
- Employee code verification
- Department identification from employee code
- Dynamic error messages
- Registration success page
- Confetti celebration effect
- Responsive modern UI

## Employee Code Format

The system accepts employee codes in the following format:

DEV-2026-AS-043

Where:

- DEV = Department Code
- 2026 = Year
- AS = Employee Initials
- 043 = Roll Number

Supported department codes:

| Code | Department |
|--------|-------------|
| DEV | Development |
| WEB | Website Designer |
| CRE | Creator |
| MAG | Management |

The application validates the employee code structure and maps department codes to their corresponding department names. :contentReference[oaicite:0]{index=0}

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Validation Checks

The system verifies:

- Names contain only letters
- Age is numeric
- Experience is numeric
- Employee code follows the required format
- Department code is valid
- Year contains exactly four digits
- Initials contain exactly two letters
- Roll number is numeric

These validations are performed before registration is completed. :contentReference[oaicite:1]{index=1}

## How to Run

1. Download the project files.
2. Keep `office.jpg` in the same folder as the HTML file.
3. Open `emp_prof1.html` in any web browser.

No additional installation is required.

## Why I Made This Project

I created this project to practice front-end web development concepts such as form validation, DOM manipulation, regular expressions, conditional logic, and responsive user interface design.

## Author

Ananya Saxena

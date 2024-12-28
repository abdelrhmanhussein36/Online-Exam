Online Exam and Registration System

This project is a simple web-based application built using Flask, HTML, CSS, and JavaScript to manage student registrations and facilitate online exams. 
Below is an overview of the project structure and functionality.

├── Registration.py
├── templates
│   ├── exam.html
│   └── registration.html
├── static
│   ├── project.css
│   ├── exam.css
│   └── exam.js
├── students_data.xlsx

Registration.py: The main Flask application handling routing, student registration, and exam processing.

templates/: Contains the HTML files for the registration and exam pages.

static/: Includes CSS and JavaScript files for styling and client-side functionality.

students_data.xlsx: Stores student data, including names, email addresses, scores, and percentages.



Setup Instructions

Prerequisites

Python 3.x

Flask

openpyxl

Installation

Clone the repository or copy the files to your local directory.

Navigate to the project directory:
cd C:\Users\HP.SXT010\Desktop\ITI\Python (or add your navigation direction)

Install required Python packages:
pip install flask openpyxl

Run the Application
python Registration.py

Open your browser and navigate to:
http://127.0.0.1:5000/registration



Python File

Registration.py:

Implements routes for registration (/registration) and exam (/exam).

Handles form submissions and JSON responses for exam scores.

Saves student data to an Excel file.



HTML Files

registration.html:

Contains a form for student registration.

Styled using project.css.

exam.html:

Displays the exam interface.

Uses exam.css for styling and exam.js for interactivity.



CSS Files

project.css:

Styles the registration page with a clean and responsive design.

exam.css:

Provides a structured layout for the exam page, including a timer and question display.

JavaScript File



exam.js:

Manages the exam functionality, including:

Mixing up questions.

Navigating between questions.

Submitting answers and handling results.




Example Usage

Navigate to the registration page, fill in the form, and submit.

Start the exam, answer the questions, and submit your answers.

View your score and percentage after submission.




Future Enhancements

Add user authentication for secure access.

Implement a database for better scalability.

Add more question types and dynamic question loading.



License

This project is licensed under the MIT License.



Acknowledgments

Developed using Flask, HTML, CSS, and JavaScript.

Thanks to ITI for guidance and support.

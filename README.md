Student Information Form - Flask Application
Overview:
This Flask-based web application allows users to submit student information via a web form, which is then saved into an Excel file. After submission, the user is redirected to a confirmation page showing that the form has been submitted successfully.

Key Features:
A simple HTML form to collect student information (name, email, age, gender, and course).
Data is saved into an Excel file (students_data.xlsx) using the openpyxl library.
After form submission, the user is redirected to a "Form Submitted Successfully" page with an option to return to the form.
Prerequisites
To run this application, you will need to have the following installed on your system:

Python 3.x
Flask (pip install Flask)
Openpyxl (pip install openpyxl)
Project Structure:
.
├── backend.py            # Main Flask application
├── students_data.xlsx     # Excel file where submitted data will be saved (generated after form submission)
└── README.md              # Documentation for the project

How to Run the Application
--Clone the repository (or download the files).
git clone <repository-url>

--Navigate to the project directory.
cd flask-form-app

--Install required dependencies.
Use pip to install the necessary Python libraries:
pip install Flask openpyxl

--Run the Flask application.
Start the Flask development server by running:
python backend.py

--Open the application in your browser.

--Once the server is running, navigate to the following address in your browser:
http://127.0.0.1:5000/

--Submit the Form.
--Fill in the required fields (name, email, age, gender, and course) and submit the form.
--Check the Excel file.
--After submitting the form, the entered data will be saved to students_data.xlsx in the project folder.

Application Workflow
Form Page: The user fills out a form with the following fields:
Full Name
Email
Age
Gender (Male/Female/Other)
Course
Form Submission: Upon submission, the data is saved in an Excel file (students_data.xlsx) with the following headers: Name, Email, Age, Gender, and Course.
Confirmation Page: After successfully saving the data, the user is redirected to a success page that confirms the submission. The user can choose to return to the form.

Technologies Used
Backend: Flask (Python)
Frontend: HTML, CSS
Data Handling: Openpyxl (to save data in Excel format)
Future Improvements
Add form validation to enhance the quality of submitted data.
Implement authentication for more secure access to the form.
Add features to allow users to download or view the saved data.

License
This project is licensed under the MIT License. Feel free to use and modify it as needed.

Author
Aveena Sanjay Dange







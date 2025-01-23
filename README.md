This Python script is a Quiz Application designed to test users on topics like SQL, Python, Power BI, Tableau, and more. Here’s a quick breakdown of its functionality:

Key Features:
Random Question Selection:

Selects 5 random questions from a predefined list for each quiz session.
Answer Validation:

Ensures that the user inputs a valid answer (between 1 and 4).
Alerts users for incorrect inputs and provides the correct answer if wrong.
Phone Number Validation:

Ensures the entered phone number is 10 digits and unique (not already in the saved data).
Score Calculation:

Tracks the number of correct answers and calculates the score out of 5.
Data Storage in Excel:

Saves user details (Name, Age, Phone, Score, and Quiz Date/Time) into an Excel file (QuizData.xlsx).
Creates the file if it doesn't exist and appends new data if it does.
User-Friendly Prompts:

Displays the question with multiple-choice options in a clear format.
How It Works:
Users are prompted to enter their name, age, and phone number.
The program ensures that phone numbers are valid and unique.
Random questions are presented, and users answer by entering a number (1-4).
At the end of the quiz, the score is displayed, and all details are saved in an Excel file.
This is a practical, beginner-to-intermediate level Python project that demonstrates the use of:

File handling (openpyxl for Excel files)
Input validation
Random sampling
Modular programming with functions

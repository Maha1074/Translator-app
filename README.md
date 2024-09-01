# Translator-app
Language Translator App
Overview
The Language Translator App is a simple desktop application built using Python's tkinter library. It allows users to translate text from one language to another using the googletrans library, which interacts with the Google Translate API.

Features
Text Input: Users can enter text in the first text box.
Language Selection: Users can choose the language they wish to translate the text into from a dropdown menu.
Translation: The translated text will appear in the second text box after pressing the "Translate" button.
Clear Functionality: Users can clear both text boxes using the "Clear" button.
Requirements
Python 3.x
tkinter (usually included with Python installations)
googletrans library
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/translator-app.git
cd translator-app
Install Required Packages: Make sure you have googletrans installed:

bash
Copy code
pip install googletrans==4.0.0-rc1
How to Run
Open a terminal or command prompt.
Navigate to the directory where the translator-app.py is located.
Run the application using Python:
bash
Copy code
python translator-app.py
How to Use
Enter the text you want to translate in the first text box.
Choose the language you want to translate into from the dropdown menu.
Click the "Translate" button to get the translation in the second text box.
To clear the text boxes, click the "Clear" button.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
The app uses the googletrans library for translation, which is a wrapper for the Google Translate API.

WikiWizard
WikiWizard is a web application that allows users to search for information on Wikipedia, get instant summaries, and translate the content into various languages. It also features voice recognition for input and text-to-speech for reading out responses.

Features
Instant Wikipedia summaries for user queries.
Translation of summaries into multiple languages.
Voice recognition for user queries.
Text-to-speech for reading out summaries.
A sleek and interactive user interface.
Technologies Used
Python
Flask
Wikipedia API
Google Translate API
HTML/CSS/JavaScript
SpeechRecognition API
Text-to-Speech API
Setup Instructions
Prerequisites
Python 3.6 or higher
Flask
wikipedia-api
googletrans==4.0.0-rc1
Installation
Clone the repository:

Clone This  repository.
Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

pip install -r requirements.txt
Run the Flask application:

flask run
The application should now be running on http://127.0.0.1:5000.

File Structure
wikiwizard/ │ ├── templates/ │ ├── index.html │ ├── chat.html │ ├── static/ │ ├── styles.css │ ├── black.mp4 │ ├── app.py ├── requirements.txt └── README.md

Usage
Open a web browser and go to http://127.0.0.1:5000.
On the home page, click on "Go to Chat" to navigate to the chat interface.
Enter your query in the text box, select the language for the response, and click "Send".
Optionally, use the voice recognition feature to input your query by clicking the "Start Voice" button.
To hear the response, click the "Read Out" button.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
Flask
Wikipedia API
Google Translate API

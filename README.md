# AI-Powered-Flashcard-Study-Automation-System

## Description 
This project is an intelligent Python-based study assistant that generates Anki flashcards from raw study notes using OpenAI's GPT API and logs the duration of study sessions to Google Calendar. It is designed to streamline and enhance the learning process through automation, real-time tracking, seamless integration with existing productivity tools, and increased student productivity. 


## Features
1. Generates context-aware flashcards using OpenAI’s language model
2. Creates .apkg files compatible with Anki for spaced repetition learning
3. Automatically logs study session durations to Google Calendar
4. Supports OAuth 2.0 authentication for secure calendar integration
5. Modular and extensible design for easy customization

## Installation 
1. Clone the repository
   git clone https://github.com/LexieChen1/AI-Powered-Flashcard-Study-Automation-System.git
   cd AI-Powered-Flashcard-Study-Automation-System
2. Install required packages
   pip install -r requirements.txt

## API configuration 
1. OpenAI API
   - Create an API key from OpenAI’s platform.
   - Set it in your script (or as an environment variable for security).
2. Google Calendar API
   - Go to the Google Cloud Console.
   - Enable the Google Calendar API.
   - Create OAuth 2.0 credentials and download the credentials.json file.
   - Place the file in the project root directory.
  
## Usage 
1. Run the script:
   - python main.py
2. When prompted, select your pdf file using file picker dialog
3. The script will:
   - Extract your notes from the selected PDF
   - Generate flashcards using GPT
   - Export an Anki .apkg deck
   - Log the study session duration to your Google Calendar
  
## License
This project is licensed under the MIT License. See LICENSE for details.




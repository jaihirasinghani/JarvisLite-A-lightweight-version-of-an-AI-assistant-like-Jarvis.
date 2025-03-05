# JARVIS Lite - AI Voice Assistant

## Overview
JARVIS Lite is an intelligent voice assistant that can recognize speech, respond to queries, execute system commands, 
and learn from interactions. It integrates speech recognition, text-to-speech, Hugging Face API, and custom memory storage to enhance conversations.

## Features
🎙️ Voice Interaction – Converts speech to text and replies using text-to-speech.
🧠 Memory System – Remembers past conversations using bot_memory.json.
🌍 Web Integration – Opens websites like Google, YouTube, and Wikipedia.
🤖 AI Responses – Uses Hugging Face API for intelligent answers.
💻 System Commands – Can open applications like Notepad, Calculator, and Browser.
🤣 Joke Generator – Tells jokes using the pyjokes library.

## Installation Guide

## 1️⃣ Prerequisites
Ensure you have Python installed. If not, download it from python.org.

## 2️⃣ Clone the Repository
Run the following command to clone the project:


git clone https://github.com/YOUR_USERNAME/JARVIS-Voice-Assistant.git
cd JARVIS-Voice-Assistant

## 3️⃣ Install Dependencies
Run the following command to install all required dependencies:

### bash
pip install -r requirements.txt
Your requirements.txt should include:

### nginx
Copy
pyttsx3  
SpeechRecognition  
requests  
datetime  
pyjokes  

## 4️⃣ Set Up API Key
Get an API Key from Hugging Face.
Replace "YOUR API KEY" in the script with your actual key.
OR store it securely in a .env file to keep it private.

## Usage
Run the assistant using:

### bash
python jarvis.py
Say "Hey Jarvis" to activate the assistant.

## Example Commands
Command	Response
"Hey Jarvis"	Greets the user.
"What is your name?"	"My name is Jarvis."
"Who made you?"	Says the creator's name.
"What time is it?"	Tells the current time.
"Search Python"	Opens Google search.
"Open YouTube"	Opens YouTube in browser.
"Tell me a joke"	Says a joke.
"Exit"	Ends the program.

## How Memory Works
JARVIS Lite remembers past interactions using bot_memory.json:

Checks stored memory before responding.
If the question is new, it queries Hugging Face API.
Saves the answer to bot_memory.json.
Next time, JARVIS will respond instantly without using the API.

## Project Structure

📂 JARVIS-Voice-Assistant/
│── 📜 jarvis.py               # Main script  
│── 📜 bot_memory.json         # Memory file (ignored in Git)  
│── 📜 requirements.txt        # Dependencies  
│── 📜 .gitignore              # Ignored files list  
│── 📜 README.md               # Documentation  

## Ignoring bot_memory.json in GitHub
To prevent storing memory data in GitHub, add this to .gitignore:
### pgsql
bot_memory.json
This ensures your private memory data is not shared publicly.

## Customization
You can modify JARVIS to fit your needs:

Change the voice settings in pyttsx3.
Add new commands in the if-elif blocks.
Modify the wake word ("Hey Jarvis") in the script.

## Troubleshooting
### 🔴 Issue: No Speech Detected
### ✅ Solution: Ensure your microphone is working and try:

### python
recognizer.adjust_for_ambient_noise(source)
### 🔴 Issue: Text-to-Speech Not Working
### ✅ Solution: If pyttsx3 does not work, try reinstalling:

### bash
pip uninstall pyttsx3
pip install pyttsx3
Or modify the script:

###  python
engine.setProperty('voice', voices[1].id)
### 🔴 Issue: API Not Responding
### ✅ Solution:

Check your Hugging Face API key and internet connection.
Ensure the API key is correct.









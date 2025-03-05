# Jarvis AI - Intelligent Voice Assistant.

## Overview

Jarvis AI is an advanced voice assistant capable of recognizing speech, responding intelligently, executing system commands, and learning from user interactions. It integrates speech recognition, text-to-speech, machine learning (Hugging Face API), and custom knowledge storage to provide a seamless conversational experience.

## Features

Speech Recognition: Uses speech_recognition to convert spoken language into text.

Text-to-Speech (TTS): Utilizes pyttsx3 for voice responses.

Custom Knowledge Storage: Learns and remembers responses using a local JSON memory file.

Hugging Face AI Integration: Queries an AI model for intelligent responses.

System Control: Opens applications (Notepad, Calculator, YouTube, etc.).

Web Search: Performs Google searches.

Error Handling: Detects and corrects incomplete user queries.

## Installation

## Prerequisites

Ensure you have Python 3.7+ installed along with the required dependencies:

pip install pyttsx3 speechrecognition requests webbrowser datetime pyjokes json difflib

## API Key Setup

Replace HUGGINGFACE_API_KEY in the script with your Hugging Face API key.

## Usage

Run the Python script:

python jarvis.py

## Commands Supported:

"Hey Jarvis" - Activates the assistant.

"Who made you?" - Replies with creator information.

"What time is it?" - Provides the current time.

"Search [query]" - Opens a Google search.

"Open Notepad", "Open Calculator" - Launches system applications.

"Exit", "OK Thanks" - Ends the session.

General Knowledge Questions - Responds based on stored knowledge or Hugging Face API.

## How It Works

Speech Recognition: Converts user speech into text.

Query Processing: Matches the input against stored knowledge.

Intelligent Response:

If an answer is found in memory, it responds immediately.

If not, it queries the Hugging Face AI model.

Learning Mechanism: Stores new valid responses into a JSON file.

System Interaction: Executes commands such as opening applications.

## Memory Storage

Jarvis maintains a knowledge base using bot_memory.json, allowing it to learn over time. If a query is repeated, it recalls the stored response.

## Customizing Bot Memory

A bot memory file (bot_memory.json) is included, containing general knowledge data. Users can freely edit and expand this file to add new information or improve existing responses. This enables Jarvis to grow smarter over time based on user input.

## Future Enhancements

Improved NLP: Enhance understanding using a more advanced AI model.

Multi-User Voice Recognition: Support recognizing different users.

More System Commands: Extend functionality for file management, automation, etc.

GUI Interface: Develop a user-friendly graphical interface.

## License

This project is open-source under the MIT License.

## Contributors

Developed by Jai Hirasinghani. Contributions and suggestions are welcome!

## Contact

For feedback or improvements, feel free to reach out.

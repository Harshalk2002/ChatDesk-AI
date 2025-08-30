# ChatDesk AI – ChatGPT Tkinter Desktop App

[![GitHub](https://badgen.net/badge/icon/GitHub?icon=github&color=black&label)](https://github.com/your-username)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)](https://www.python.org)
[![OpenAI API](https://img.shields.io/badge/OpenAI_API-00A67E?logo=openai&logoColor=white)](https://platform.openai.com/)

---

## Overview
**ChatDesk AI** is a Python-based desktop application for interacting with OpenAI’s ChatGPT models.  
Built with **Tkinter + CustomTkinter**, it provides a simple, modern interface that allows you to run ChatGPT locally on your computer using your own API key.  

Key highlights:
- Easy-to-use desktop client for ChatGPT  
- Model selection (GPT-4o, GPT-4o mini, o1, etc.)  
- Conversation history within a session  
- Optional text-to-speech playback of responses  

---

## Features
- **User Interface**: Clean and responsive, built with Tkinter and CustomTkinter  
- **Model Selection**: Switch between multiple GPT models  
- **Conversation History**: Review your past exchanges within the app  
- **Audio Playback**: Listen to ChatGPT’s responses (optional)  
- **API Key Manager**: Update and manage your OpenAI key directly in the app  

---

## Repository Structure
ChatDesk-AI/
├── MAIN.py # Main application (Tkinter GUI)
├── bot.py # ChatGPTBot class (API + TTS logic)
├── icons/ # Application icon (chat.ico)
├── requirements.txt # Dependencies
├── README.md # Documentation
└── LICENSE

---

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ChatDesk-AI.git
   cd ChatDesk-AI
Install dependencies


pip install -r requirements.txt
Set your OpenAI API key

macOS/Linux:


export OPENAI_API_KEY="your_api_key_here"
Windows (PowerShell):


Copy code
setx OPENAI_API_KEY "your_api_key_here"
Run the application



python MAIN.py
Example Usage
Enter your API key and select a GPT model

Type your message and press Enter to chat

(Optional) Use the “Play” button to hear the response

Contributions
Contributions are welcome. Please open an issue or submit a pull request with improvements or bug fixes.

License
This project is licensed under the MIT License.

Author
Developed by Harshal Kamble

LinkedIn: [linkedin.com/in/your-linkedin](https://www.linkedin.com/in/harshalka/)



---

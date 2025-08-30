# ChatGPT Tkinter Desktop App

[![GitHub](https://badgen.net/badge/icon/GitHub?icon=github&color=black&label)](https://github.com/MaxineXiong)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Python](https://img.shields.io/badge/Python->=3.6-blue?logo=python&logoColor=white)](https://www.python.org)
[![OpenAI API](https://img.shields.io/badge/OpenAI_API-E5E4E2?logo=OpenAI&logoColor=%23000000)](https://openai.com/blog/openai-api)
[![ChatGPT](https://img.shields.io/badge/ChatGPT-00A67E?logo=openai)](https://chat.openai.com/)

<br/>
# ChatDesk AI – ChatGPT Tkinter Desktop App

## Overview
ChatDesk AI is a lightweight desktop client for ChatGPT, built using **Python (Tkinter + CustomTkinter)**.  
It provides an easy-to-use interface for interacting with OpenAI’s models directly from your computer.

This project demonstrates skills in **GUI development, API integration, and software design**.

---

## Features
- User-friendly **Tkinter-based desktop interface**
- Integration with **OpenAI Chat Completions API**
- **Model selection** (e.g., GPT-4o, GPT-4o mini, o1)
- **Conversation history** within the session
- **Text-to-speech playback** (optional)
- Simple **API key management** inside the app

---

## Project Structure
ChatDesk-AI/
├── MAIN.py # Main Tkinter GUI
├── bot.py # ChatGPTBot class (API + TTS logic)
├── requirements.txt # Dependencies
├── icons/ # App icon (chat.ico)
└── README.md # Documentation

yaml
Copy code

---

## Installation and Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/ChatDesk-AI.git
   cd ChatDesk-AI
Install dependencies

bash
Copy code
pip install -r requirements.txt
Set your OpenAI API Key

macOS/Linux:

bash
Copy code
export OPENAI_API_KEY="your_api_key_here"
Windows (PowerShell):

powershell
Copy code
setx OPENAI_API_KEY "your_api_key_here"
Run the application

bash
Copy code
python MAIN.py
Tech Stack
Language: Python 3.9+

Libraries: Tkinter, CustomTkinter, OpenAI API, pyttsx3 (TTS)

Platform: Cross-platform (Windows, macOS, Linux)

Author
Developed by Harshal Kamble

LinkedIn: linkedin.com/in/your-linkedin

GitHub: github.com/your-username


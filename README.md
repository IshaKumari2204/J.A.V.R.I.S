# J.A.V.R.I.S – Voice-Controlled AI Assistant

J.A.V.R.I.S is a Python-based voice assistant that responds to spoken commands to perform tasks like opening websites, telling the time, launching applications, playing music, and chatting using OpenAI’s GPT-3.

## 🔧 Features
- 🎙️ Voice input using Google SpeechRecognition
- 💬 GPT-3 powered conversational replies
- 🔊 Voice output via macOS TTS (`say` command)
- 🌐 Opens sites like YouTube, Google, Wikipedia
- 🕒 Tells current time and automates basic tasks

## 🛠️ Tech Stack
- Python
- OpenAI API (`text-davinci-003`)
- SpeechRecognition
- OS-level automation (macOS)

## 🚀 Getting Started
1. Clone the repo
2. Install dependencies:  
   `pip install openai SpeechRecognition`
3. Add your OpenAI API key in `config.py`
4. Run:  
   `python main.py`

## 📌 Note
Currently supports macOS only (due to `say` and app paths).

# 🤖 Jarvis - Voice Activated Virtual Assistant

Jarvis is a **Python-based Voice Activated Virtual Assistant** that performs everyday tasks through voice commands. It listens for the wake word **"Jarvis"**, understands spoken commands, and responds with natural voice output.

Unlike traditional assistants, this project uses the **Grok API** for intelligent conversational responses, making it free to use without relying on OpenAI APIs.

---

## ✨ Features

- 🎙️ Wake word detection ("Jarvis")
- 🗣️ Speech Recognition
- 🤖 AI-powered conversations using **Grok API**
- 🔊 Text-to-Speech using **pyttsx3** and **gTTS**
- 🌐 Open websites with voice commands
- 🎵 Play music
- 📰 Fetch latest news
- ⚡ Fast command processing
- 🧩 Modular and easy-to-understand Python code

---

## 🛠️ Tech Stack

- Python
- Grok API
- SpeechRecognition
- pyttsx3
- gTTS
- pygame
- requests
- webbrowser

---

## 📂 Project Structure

```
Jarvis/
│
├── main.py
├── client.py
├── musicLibrary.py
├── config.py
├── requirements.txt
├── README.md
└── assets/
```

---

## ⚙️ Workflow

### 1. Initialization

Jarvis starts by greeting the user.

```
Initializing Jarvis...
```

---

### 2. Wake Word Detection

Jarvis continuously listens for the wake word.

```
Jarvis
```

---

### 3. Activation

After detecting the wake word, Jarvis responds:

```
Ya.
```

---

### 4. Command Processing

Jarvis identifies the user's command and performs actions such as:

- Opening websites
- Playing music
- Fetching news
- Answering questions using the Grok API

---

### 5. Speech Output

Jarvis replies using Text-to-Speech powered by:

- pyttsx3
- gTTS

---

## 📚 Libraries Used

- SpeechRecognition
- pyttsx3
- gTTS
- pygame
- requests
- webbrowser
- os
- Grok API
- musicLibrary

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/Jarvis-Voice-Activated-Virtual-Assistant.git
```

---

### Navigate to the project

```bash
cd Jarvis-Voice-Activated-Virtual-Assistant
```

---

### Install dependencies

```bash
pip install -r requirements.txt
```

---

### Configure API Key

Create a configuration file or environment variable for your **Grok API Key**.

Example:

```python
GROK_API_KEY = "YOUR_API_KEY"
```

---

### Run the project

```bash
python main.py
```

---

## 💬 Example Commands

- Open YouTube
- Open Google
- Play music
- What's the latest news?
- Tell me a joke
- Explain Artificial Intelligence
- What is Python?
- Open GitHub

---

## 🎯 Future Improvements

- GUI Dashboard
- Weather Updates
- Email Automation
- Calendar Integration
- WhatsApp Messaging
- Smart Home Control
- Reminder & Alarm System
- Face Recognition Login
- Multi-language Support
- Offline AI Model Support

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is licensed under the Apache 2.0 License.

---

## 👨‍💻 Author

**Dhanraj Kumar**

Software Engineer | Python Full-Stack Developer

If you like this project, don't forget to ⭐ the repository.

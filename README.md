# Jarvis-Voice-Activated-Virtual-Assistant
Jarvis is a voice-activated virtual assistant designed to perform tasks such as web browsing, playing music, fetching news, and responding to users queries using OpenAI's GPT-3.5-turbo model.

Jarvis – Voice Activated Virtual Assistant | Python, Grok API
• Developed a voice-controlled virtual assistant for task automation and AI-based responses
• Implemented voice recognition using SpeechRecognition with wake word detection ("Jarvis")
• Integrated LLM-based API (Grok) for intelligent query handling and conversational responses
• Built text-to-speech system using pyttsx3 and gTTS for real-time voice interaction
• Automated web browsing, music playback, and news fetching using APIs and Python modules
• Designed modular command-processing workflow for efficient task execution
• Acts as a general virtual assistant similar to Alexa or Google Assistant.
• Activates upon detecting the wake word "Jarvis."
• Text-to-Speech

WORKFLOW
1. Initialization
2. Greets the user with "Initializing Jarvis...."
3. Wake Word Detection
4. Listens for the wake word "Jarvis."
5. Acknowledges activation by saying "Ya."
6. Command Processing.
7. Processes commands to determine actions such as opening a website, playing
music, fetching news, or generating a response via OpenAI.
8. Speech Output.
9. Provides responses using speak function with either pyttsx3 or gTTS.
10. Greets the user with "Initializing Jarvis...."
11. Wake Word Detection
12. Acknowledges activation by saying "Ya."
13. Processes commands to determine actions such as opening a website, playing
music, fetching news, or generating a response via OpenAI.

LIBRARIES USED
• speech_recognition
• webbrowser
• pyttsx3
• musicLibrary
• requests
• openai
• gTTS
• pygame
• os

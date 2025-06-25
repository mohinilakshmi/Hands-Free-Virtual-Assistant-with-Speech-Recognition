# Hands-Free-Virtual-Assistant-with-Speech-Recognition

---

````markdown


A simple yet powerful voice assistant built using Python that can understand voice commands, search Wikipedia, open websites, tell jokes, provide time, and more — all through your voice.

---

## 🚀 Features

- 🎤 Voice-activated command recognition
- 🔊 Text-to-speech responses
- 🌐 Wikipedia search
- 📺 Opens YouTube, Google, Pinterest
- ⏰ Tells current time
- 😂 Tells programming jokes
- 🛑 Start, stop, and exit via voice
- ✍️ Note-taking (optional extension)

---

## 🧰 Technologies & Libraries Used

- Python 3.7+
- `SpeechRecognition` – for converting speech to text  
- `PyAudio` – for accessing the microphone  
- `pyttsx3` – for converting text to speech  
- `wikipedia` – to fetch summary results  
- `pyjokes` – to tell random programming jokes  
- `webbrowser`, `datetime`, `re` – built-in Python libraries

---

## 🖥️ System Requirements

- Windows/macOS with Python 3.7 or higher  
- Working microphone and speakers  
- Visual Studio Code or any Python IDE

---

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/voice-assistant-python.git
cd voice-assistant-python
````

2. **Install required libraries**

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install SpeechRecognition pyttsx3 wikipedia pyjokes pyaudio
```

> ⚠️ Note: For Windows users, install `pyaudio` using:

```bash
pip install pipwin
pipwin install pyaudio
```

---

## ▶️ How to Run

```bash
python voice_assistant.py
```

Then say **"start"** to activate the assistant.

---

## 📝 Sample Commands

* "start" / "resume"
* "search Python on Wikipedia"
* "open YouTube"
* "tell me a joke"
* "what is the time"
* "stop" / "pause"
* "exit" / "bye"

```

---

### ✅ Tip:
Save this as `README.md` in your project folder. Let me know if you want the `requirements.txt` or want to include demo screenshots/GIFs in the README.
```

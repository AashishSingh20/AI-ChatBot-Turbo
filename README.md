# 🎙️ Turbo Voice Assistant

A simple Python-based voice assistant that listens for the wake word **"Turbo"** and performs tasks like opening websites, playing music, telling jokes, and providing date/time.

---

## 🚀 Features

- 🎤 **Voice recognition** (Google Speech API)  
- 🔊 **Text-to-speech responses**  
- 🌐 **Open websites** (Google, YouTube)  
- 🎵 **Play songs** from a custom music library  
- 😂 **Tell random jokes**  
- 📅 **Get current date**  
- ⏰ **Get current time**  
- 🔎 **Perform Google searches**

---

## 🛠️ Tech Stack

- **Python**
- `speech_recognition`
- `pyttsx3`
- `pyjokes`
- `webbrowser`
- `datetime`

---

## 📦 Installation

```bash
git clone https://github.com/AashishSingh20/AI-ChatBot-Turbo.git
cd AI-ChatBot-Turbo
pip install speechrecognition pyttsx3 pyjokes pyaudio

```
⚠️ If pyaudio installation fails:
```
pip install pipwin
pipwin install pyaudio
```

### ▶️ Run the Project
``` python main.py ```

---

## 🗣️ Usage

1. Run the script
2. Say "Turbo" to activate
3. Speak your command
---

## 🗣️ Supported Commands
| Command Example           | Action                    |
| ------------------------- | ------------------------- |
| "Turbo"                   | Activates assistant       |
| "Open Google"             | Opens Google              |
| "Open YouTube"            | Opens YouTube             |
| "Play [song]"             | Plays a song from library |
| "Tell me a joke"          | Tells a random joke       |
| "What is today's date"    | Speaks current date       |
| "What's the time"         | Speaks current time       |
| "Search Python tutorials" | Performs Google search    |

---

## ⚠️ Limitations
- Requires internet for speech recognition
- Limited command set
- Background noise may affect accuracy

---

## 🔮 Future Improvements
- Add more commands
- Integrate AI (ChatGPT API)
- Add GUI
- Improve wake word detection
- Add offline speech recognition
---

## 🤝 Contributing

Feel free to fork this repo and improve it!

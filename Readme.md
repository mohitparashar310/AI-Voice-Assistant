# 🤖 AI Voice Assistant (Web UI)

A Streamlit-based **AI Voice Assistant** that listens to your speech 🎙️, processes it using **LangChain + Ollama (Mistral model)**, and responds with both text and voice 🔊.  
This project demonstrates real-time **speech recognition**, **natural language processing**, and **text-to-speech synthesis** — all in one interactive web interface.

---

## 🚀 Features

- 🎤 **Voice Recognition** — Converts speech to text using Google Speech API.  
- 🧠 **Conversational Memory** — Maintains context across turns via LangChain.  
- 💬 **AI Response Generation** — Powered by Ollama (Mistral / Llama3 models).  
- 🗣️ **Text-to-Speech** — Speaks responses aloud using `pyttsx3`.  
- 🌐 **Streamlit Web Interface** — Clean, interactive UI for seamless chat experience.  

---

## 🧩 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend  | Streamlit |
| Backend   | Python |
| AI Engine | LangChain + Ollama |
| Speech I/O | SpeechRecognition, pyttsx3 |
| Model     | Mistral / Llama3 (via Ollama) |

---

## 🖥️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/mohitparashar310/AI-Voice-Assistant.git
cd AI-Voice-Assistant

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the App
streamlit run ai_voice_assistant_ui.py


⚠️ Make sure Ollama is running locally and your model (e.g., mistral or llama3) is available.

# 🏋️ AI Gym Coach

AI Gym Coach is a real-time AI-powered fitness coaching web application that helps users improve exercise form using computer vision and pose estimation. It provides live feedback, workout tracking, and AI-generated coaching insights using a webcam.

---

## 📌 Why this project?

This project demonstrates:
- Real-time **computer vision applications**
- **AI-driven feedback systems**
- Full-stack Python application development
- Integration of **ML + Web (Streamlit)**
- Practical use of **pose estimation in fitness domain**

---

## 🚀 Key Features

- 🧍 Real-time human pose detection using webcam
- 🏋️ Exercise tracking:
  - Squats
  - Push-ups
  - Biceps curls
  - Shoulder press
  - Lunges
- 📊 Live repetition counting & form tracking
- 🤖 AI-based coaching feedback system
- 🔊 Voice feedback using text-to-speech (TTS)
- 📈 Workout session tracking & progress monitoring
- 📜 Exercise history logging

---

## 🧠 Tech Stack

- Python
- Streamlit (Web UI)
- MediaPipe (Pose Detection)
- OpenCV (Computer Vision)
- streamlit-webrtc (Real-time video streaming)
- Groq API (AI Coaching / LLM integration)
- gTTS (Text-to-Speech)

---

## 📁 Project Structure

```

AI Gym Coach
├── LandingPage/         # Landing page UI
├── Main App/            # Core application
│   ├── main.py          # Entry point
│   ├── requirements.txt # Dependencies

````

---

## ⚙️ Installation

```powershell
cd "Main App"

py -m venv .venv
.\.venv\Scripts\Activate.ps1

pip install -r requirements.txt
````

---


Open in browser:

```
http://localhost:8501
```

---

## 🔐 Environment Variables

To enable AI coaching features:

```powershell id="m0xq8v"
$env:GROQ_API_KEY="your_api_key_here"
```

---

## 💡 What I Learned

* Building real-time AI applications using Python
* Integrating computer vision with web applications
* Handling live video streams in Streamlit
* Working with pose estimation models
* Designing AI-assisted feedback systems

---

## 📌 Use Cases

* Fitness coaching applications
* AI-based posture correction systems
* Rehabilitation and physiotherapy tools
* Sports training analytics


---


## 🌐 Live Demo

| Demo | Link |
|------|------|
| 🎨 Landing Page | https://ai-gym-coach-kucchi.netlify.app/ |
| 🚀 AI Gym Coach App | https://gym-ai-ktza6eugztgvzjkpumvctr.streamlit.app/ |

> **Note:** Camera permission is required for real-time pose detection and AI coaching.

# 🤖 AI-VIEW: AI Vision Assistant for Smart Glasses

> A multi-modal AI-powered assistant built for smart glasses — combining computer vision, natural language understanding, and gesture recognition into a unified experience.

**AI-VIEW** enables real-time awareness and interaction through sight, voice, emotion, and gestures — tailored for accessibility, mobility, and human-AI augmentation.

---

## 🧠 Core Features

- 🥽 **Walking Mode**  
  Detects objects (0–15m range) and estimates distance using color-coded alerts.  
  → Powered by YOLOv8 and custom proximity mapping.

- 🗣️ **Talking Mode**  
  Engage in AI conversations with natural speech using OpenAI and ElevenLabs APIs.  
  → Arabic + English support.

- 😊 **Emotion Detection Mode**  
  Detects facial expressions (happy, sad, neutral, etc.) in real time.  
  → Based on DeepFace.

- 📖 **Reading Mode**  
  Recognizes text in English and Arabic using OCR, then reads it aloud.  
  → EasyOCR + multilingual TTS.

- ✋ **Gesture Mode**  
  Recognizes hand signs using MediaPipe for intuitive control (e.g., stop, thumbs up, point).

---

## 🧩 Architecture Overview

```plaintext
📦 ai_vision_assistant/
├── ai.py                 # Main controller
├── voice.py              # Voice and TTS handling
├── .env.template         # API key structure
├── requirements.txt      # Dependencies
└── README.md             # You're here!

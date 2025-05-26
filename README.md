# 👓 AI-VIEW: AI Vision Assistant for Smart Glasses

> A multi-modal AI-powered assistant built for wearable smart glasses — empowering real-time perception, interaction, and accessibility using vision, language, gestures, and sound.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![OS](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)
![License](https://img.shields.io/github/license/0xVeRc/AI-VIEW)
![Status](https://img.shields.io/badge/Status-Active-green)
[![Author](https://img.shields.io/badge/By-0xVeRc-blueviolet)](https://github.com/0xVeRc)

---

## 🧠 Project Overview

**AI-VIEW** is an AI-driven vision assistant designed for smart glasses. It enables users — especially the visually impaired — to understand and interact with their surroundings in real time through:

- Object detection
- Emotion recognition
- Text reading (English & Arabic)
- AI-powered voice conversation
- Gesture-based control

Built with modularity and real-time performance in mind, AI-VIEW fuses advanced computer vision, speech, and NLP models into an edge-ready assistant.

---

## 🌟 Key Features

### 🧑‍🤝‍🧑 Face Recognition
- Detects and identifies known faces in real time
- Saves new faces locally using a smart face database
- Useful for remembering familiar people and providing personalized context (e.g., “Ahmed is nearby”)
- Based on **DeepFace** and face embedding comparison

### 🚶 Walking Mode (W)
- Detects surrounding objects using YOLOv8 (up to 15m range)
- Measures distance and gives **color-coded warnings**
- Ideal for navigation and obstacle avoidance

### 🗣️ Talking Mode (T)
- Voice chat with an AI agent using OpenAI
- Natural text-to-speech responses via ElevenLabs
- English & Arabic conversation support

### 😊 Emotion Detection Mode (E)
- Uses **DeepFace** to analyze nearby human expressions
- Identifies emotions like happy, sad, neutral
- Adds emotional context to conversations or alerts

### 📖 Reading Mode (R)
- Optical Character Recognition (OCR) in **English and Arabic**
- Reads signs, documents, labels aloud in real time
- Based on EasyOCR + custom Arabic tuning

### ✋ Gesture Mode (G)
- Recognizes intuitive hand gestures (e.g., stop, thumbs-up)
- Non-verbal commands without buttons or voice
- Built using MediaPipe's hand landmarks

---

## 🖼️ Screenshots

| Emotion Detection                    |
-------------------------------------|
 ![Emotion](/emotion.png) |

| Gesture Mode                     | Face Recognition                     |
|----------------------------------|--------------------------------------|
| ![Gesture](/gesture.png) | ![Face](/face_recognition.png) |

---

## Soruce Code is Private..


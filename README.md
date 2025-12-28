# SYNTECXHUB-AI_Internship_Task_Week_04_Face_Detection_Recognition
📄 Project Description:  Personal AI Voice Assistant built with Python and Google Colab. Features Speech-to-Text (STT) via Google Speech Recognition, a rule-based command engine, and Text-to-Speech (TTS) using gTTS. Includes a custom browser-to-server audio bridge to bypass Colab's hardware limitations.
# 🎙️ Personal AI Voice Assistant (Internship Project 01)

A robust, web-integrated Personal Voice Assistant developed in Python. This project demonstrates the integration of **Natural Language Processing (NLP)** concepts, **Speech-to-Text (STT)**, and **Text-to-Speech (TTS)** technologies.

Unlike standard local scripts, this version is specifically optimized to run on **Google Colab** by utilizing a JavaScript bridge for real-time browser microphone access.



## ✨ Key Features
* **Speech Recognition:** Converts spoken commands into text using the Google Speech Recognition API.
* **Intelligent Logic:** Maps user commands (Time, Web Search, Greetings) to specific automated actions.
* **Vocal Feedback:** Responds to the user in a natural voice using Google Text-to-Speech (`gTTS`).
* **Colab Compatibility:** Custom JavaScript implementation to handle audio recording in a cloud environment.
* **Error Handling:** Robust processing for background noise, unrecognized speech, and format conversion.

## 🛠️ Technologies Used
* **Python 3.x**
* **SpeechRecognition:** For processing audio data.
* **gTTS:** For generating vocal responses.
* **Pydub:** For audio format conversion (WebM to WAV).
* **FFmpeg:** Backend engine for audio processing.
* **IPython:** For handling audio playback and JS integration in Colab.

## 🚀 Installation & Usage
### 1. Prerequisites
Since this is a Google Colab project, no local installation is required. However, you must ensure the following system dependencies are installed within the notebook:
```bash
!apt-get install -y ffmpeg
!pip install SpeechRecognition gTTS pydub

# 🎓 AI Multimodal Attendance System (Face & Voice Biometrics)

An advanced, AI-powered attendance management system built for educational institutions to automate student verification using multimodal biometrics (**Facial Recognition** and **Voice Identification**). The system features a full-featured **Streamlit** dashboard for attendance logging, automated database synchronization, and an interactive landing page showcasing the product workflow deployed on **Vercel**.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-FF4B4B)
![Vercel](https://img.shields.io/badge/Deployment-Vercel-000000)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-ee4c2c)
![OpenCV](https://img.shields.io/badge/Vision-OpenCV-green)
![Domain](https://img.shields.io/badge/Domain-AI%20%26%20Biometrics-purple)

---

## 📌 Executive Summary

Traditional attendance taking in classrooms is time-consuming and prone to proxy records. This multimodal biometric solution combines computer vision and speaker recognition to ensure high-accuracy verification. Teachers can launch real-time face/voice scanning through an intuitive Streamlit app, while students and administrators can explore system capabilities through a dedicated landing page.

---

## 🛠️ System Architecture & Biometric Workflow

### 1. Facial Recognition Engine
- **Face Detection & Alignment:** Real-time stream processing using OpenCV to isolate facial bounding boxes.
- **Deep Feature Embedding:** Generates facial vector embeddings and calculates cosine similarity against registered student profiles for instant matching.

### 2. Voice Identification Pipeline
- **Audio Capture & VAD:** Voice Activity Detection (VAD) filters out background noise and isolates active student speech audio samples.
- **Speaker Verification:** Extracts voice embeddings (d-vectors) to verify individual acoustic signatures against stored voice profiles.

### 3. Application UI & Landing Page Deployment
- **Streamlit App Interface:** Interactive multi-page dashboard allowing instructors to take class attendance, manage student enrollments, and export attendance logs.
- **Vercel Landing Page:** Responsive web landing page showcasing product features, system architecture, visual workflows, and project documentation.
- **App Link:** https://major-project-landing-page.vercel.app/

---

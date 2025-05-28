<h1 align="center">🌿 Plant Disease Detector</h1>
<p align="center">
  <strong>AI-powered plant health assistant for farmers</strong><br>
  Built with <code>Python</code>, <code>TensorFlow</code>, <code>FastAPI</code>, and <code>React Native</code>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-AI%20Model-blue?logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-Model-orange?logo=tensorflow" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-green?logo=fastapi" />
  <img src="https://img.shields.io/badge/React%20Native-Mobile-61dafb?logo=react" />
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow" />
</p>

---

## 🌾 Project Overview

**Plant Disease Detector** is a smart mobile system that helps farmers detect diseases in plant leaves using image classification. It uses a custom-trained **TensorFlow** model served via a **FastAPI** backend, with a user-friendly mobile interface built in **React Native**.

---

## ✨ Features

- 📸 Upload a leaf photo and get disease diagnosis
- 🔍 Classifies leaves as: `Healthy`, `Early Blight`, or `Late Blight`
- 🔁 Real-time FastAPI backend response
- 📱 Mobile-first interface for farmers
- 📊 TensorFlow model optimized for performance on mobile uploads
- ⚠️ Error handling when no valid leaf is detected

---

## 🔧 Tech Stack

| Layer        | Technology           |
|--------------|----------------------|
| 🤖 AI Model   | Python + TensorFlow  |
| 🔌 API Server | FastAPI              |
| 📱 Frontend   | React Native (Expo)  |
| 🧪 Testing    | Postman, Android Emulator |
| 🌍 Hosting    | (Optional) Render, Railway, or local server |

---

## 🧠 AI Model

- Trained on a labeled dataset of plant leaves (`Healthy`, `Early Blight`, `Late Blight`)
- Preprocessing: image resizing, normalization
- Architecture: CNN (Custom or MobileNetV2)
- Saved model format: `.h5` or `SavedModel` directory

---

## 🚀 Getting Started

### 🔥 Backend (FastAPI + TensorFlow)

```bash
# Clone the repository
git clone https://github.com/your-username/plant-disease-detector.git
cd backend

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the FastAPI server
uvicorn main:app --reload

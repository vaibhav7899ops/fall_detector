# 🩺 Smart Fall-Risk Predictor

A wearable AI-powered system that continuously monitors vital signs and movement patterns to predict and prevent fall risks in real time. Designed for elderly individuals and patients with mobility challenges, it uses machine learning and sensor data to trigger early alerts and enable timely interventions.

---

## 🚀 Features

- 🎯 Predicts fall risk using a trained ML model
- 📊 Real-time tracking of:
  - Heart Rate Variability (HRV)
  - Blood Pressure
  - Blood Sugar Level
  - SpO₂ (Blood Oxygen)
  - Accelerometer (Motion/Gait)
- 🔔 Instant alerts for users and caregivers
- 🗣️ Voice-based alerts using Web Speech API
- 🌐 3D-style holographic smartwatch web interface

---

## 🧠 How It Works

1. User inputs six key vitals (or they are streamed from sensors).
2. The backend ML model evaluates the input data.
3. If fall risk is above a threshold (e.g., 0.3), alerts are triggered.
4. Output includes: predicted class, risk probability, and alert message.

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Backend:** Python Flask API
- **Machine Learning:** Scikit-learn
- **Voice Alerts:** Web Speech API (`SpeechSynthesisUtterance`)
- **3D UI Visual:** CSS + Image-based simulation (watch + hologram)

---

## 📂 Project Structure
healthy_hackers/
├── app.py # Flask backend server
├── train_model.ipynb # Notebook for training the ML model
├── custom_fall_risk_model.pkl # Pre-trained ML model
├── templates/
│ └── index.html # Main web interface
├── static/
│ └── images/ # Watch & background images
└── README.md

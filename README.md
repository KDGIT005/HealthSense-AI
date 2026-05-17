<div align="center">

# 🩺 HealthSense AI

**An AI-powered health monitoring system built for Android**  
*Machine Learning · Generative AI · Virtual Smartwatch Simulation*

[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Language-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Firebase](https://img.shields.io/badge/Auth-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Gemini](https://img.shields.io/badge/AI-Gemini-4285F4?style=flat-square&logo=google&logoColor=white)](https://ai.google.dev)
[![Flask](https://img.shields.io/badge/Backend-Flask-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![License](https://img.shields.io/badge/License-Educational-blue?style=flat-square)](#license)

<br/>

> HealthSense AI simulates a full wearable health ecosystem — from biometric data collection and ML-based risk prediction to personalized AI recommendations — without requiring any physical hardware.

</div>

---

## ✨ What It Does

HealthSense AI brings together three intelligent systems in a single Android app:

- **A virtual smartwatch** that streams realistic biometric readings every 10 seconds
- **A cloud-hosted ML model** that classifies your health risk in real time
- **Google Gemini AI** that turns those predictions into actionable, personalized advice

---

## 📱 Screens at a Glance

| Screen | Description |
|--------|-------------|
| **Onboarding** | 3-slide intro + Get Started flow |
| **Auth** | Email login & signup via Firebase |
| **Dashboard** | Live biometric feed, smartwatch status, risk summary |
| **Predictions** | ML risk output + Gemini-generated suggestions |
| **Self Assessment** | Manual input for sleep, stress, and blood pressure |
| **Insights** | Health trend cards and 7-day summaries |
| **Profile** | User details, watch connection, app info |

---

## 📸 Screenshots

<div align="center">

| 🏠 Dashboard | 📊 Insights | 🤖 AI Predictions |
|:---:|:---:|:---:|
| <img width="716" height="1600" alt="WhatsApp Image 2026-04-05 at 9 05 56 PM (2)" src="https://github.com/user-attachments/assets/e8f2d994-1008-4ede-8858-cf6acbe3d528" /> | <img width="716" height="1600" alt="WhatsApp Image 2026-04-05 at 9 05 56 PM (1)" src="https://github.com/user-attachments/assets/7c93ed4f-3f17-4e30-bcc2-f05db9551728" /> | <img width="716" height="1600" alt="WhatsApp Image 2026-04-05 at 9 05 56 PM" src="https://github.com/user-attachments/assets/b28b0c34-37ea-4981-b773-9d5e5b185a4b" /> |
| Live biometric feed & smartwatch status | 7-day heart rate, SpO₂ & sleep trends | ML risk level + Gemini suggestions |

</div>

---

## ⚙️ How It Works

```
Virtual Smartwatch Simulator
         │  (every 10 seconds)
         ▼
   Android App (Kotlin + MVVM)
         │
         ▼
  Self-Assessment Module
         │
         ▼
  ML Prediction API  ──── Render Cloud (Flask + Scikit-learn)
         │
         ▼
   Health Risk Level
  🟢 Low · 🟡 Medium · 🔴 High
         │
         ▼
  Gemini AI Recommendation Engine
         │
         ▼
  Personalized Preventive Suggestions
```

### Simulated Biometrics

| Parameter | Description |
|-----------|-------------|
| ❤️ Heart Rate | BPM reading |
| 🫁 SpO₂ | Blood oxygen saturation |
| 🌡️ Body Temperature | Core temp in °C |
| 😴 Sleep Hours | Nightly rest estimate |
| 😰 Stress Level | Lifestyle stress index |
| 🩸 Blood Pressure | Systolic & diastolic |

### ML Input Features

```
heart_rate · spo2 · body_temp · sleep_hours
stress_level · systolic_bp · diastolic_bp · age
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Language | Kotlin |
| Architecture | MVVM |
| UI | Material 3 + XML |
| Auth | Firebase Authentication |
| Networking | Retrofit + OkHttp |
| Async | Coroutines + StateFlow |
| AI Recommendations | Google Gemini API |
| ML Model | Scikit-learn |
| Backend | Python Flask |
| Cloud Hosting | Render |

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/KDGIT005/HealthSense-AI.git
cd HealthSense-AI
```

### 2. Open in Android Studio

Use **Android Studio Giraffe** or newer. Let Gradle sync complete.

### 3. Add your API key

Create or edit `local.properties` in the project root:

```properties
GEMINI_API_KEY=your_gemini_api_key_here
```

> Get a free Gemini API key at [ai.google.dev](https://ai.google.dev)

### 4. Build & run

```bash
./gradlew assembleDebug
```

Or hit **Run ▶** in Android Studio on an emulator or physical device.

---

## 📂 Project Structure

```
HealthSense-AI/
├── app/
│   ├── ui/               # Screens & fragments
│   ├── adapters/         # RecyclerView adapters
│   ├── models/           # Data models
│   ├── network/          # Retrofit API clients
│   ├── utils/            # Helpers & extensions
│   └── viewmodel/        # MVVM ViewModels
│
├── healthsense-api/
│   ├── app.py            # Flask app entry point
│   ├── model/            # Trained Scikit-learn model
│   └── requirements.txt
│
├── build.gradle
└── settings.gradle
```

---

## 🔭 Roadmap

- [ ] Real smartwatch integration (Wear OS / Health Connect)
- [ ] Historical analytics dashboard
- [ ] TensorFlow Lite on-device inference
- [ ] AI health chatbot
- [ ] Emergency alert system
- [ ] Cloud sync for multi-device support
- [ ] Multi-user monitoring profiles

---

## 🔐 Security Notes

- API keys are stored in `local.properties` (gitignored — never committed)
- Firebase handles session management and token refresh
- All API communication is over HTTPS

---

## 👨‍💻 Author

**Kuldeep Dhangad**  
Android Developer · AI/ML Enthusiast · Cloud & Backend Learner

[![GitHub](https://img.shields.io/badge/GitHub-KDGIT005-181717?style=flat-square&logo=github)](https://github.com/KDGIT005)

---

## 📄 License

This project is built for **educational and portfolio purposes**.  
Feel free to explore, fork, and learn from it.

---

<div align="center">

If you found this useful, consider giving it a ⭐ — it helps a lot!

</div>

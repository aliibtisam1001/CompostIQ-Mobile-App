# 🌱 CompostIQ — Smart Composting Mobile App

> **AI + IoT Smart Composting Research Project**  
> Albukhary International University (AIU), Kedah, Malaysia  
> Built for Student Research Assistant (Mobile App Developer) Application

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![IoT](https://img.shields.io/badge/IoT-ESP32-000000?logo=espressif&logoColor=white)](https://www.espressif.com/)

---

## 📱 Live Demo

**Open on your phone:** [GitHub Pages Link](https://aliibtisam1001.github.io/CompostIQ-Mobile-App/Project1_CompostIQ_MobileApp.html)  
*Or download the HTML file and open it in any mobile browser — it works offline!*

![App Preview](assets/demo-preview.gif)

---

## ✨ Features

### 🏠 Home Dashboard
- **Real-time sensor cards** — Temperature, Moisture, pH, CO₂ with color-coded status indicators
- **AI Recommendation engine** — Smart insights based on current sensor readings
- **Activity feed** — Track compost additions, turns, and weekly reports
- **Header stats** — Active bins count, average health score, active alerts

### 📊 Analytics Screen
- **Decomposition rate chart** — Weekly organic breakdown visualization
- **Key metrics grid** — Overall efficiency, cycle time, waste diverted, AI accuracy
- **Health score ring** — Visual progress indicator with parameter breakdown
- **Trend indicators** — Up/down arrows showing week-over-week improvement

### 📡 IoT Devices Screen
- **Device status cards** — Online/offline badges for each ESP32 sensor
- **Live sensor readings** — Temperature, moisture, pH with color-coded dots (🟢🟡🔴)
- **AI recommendations per device** — Actionable alerts ("Turn Compost", "Add Carbon")
- **Last updated timestamps** — Real-time sync status

### 🤖 AI Chat Assistant
- **Smart composting assistant** — Ask questions about bins, sensors, or tips
- **Contextual responses** — Powered by rule-based ML logic (simulated for demo)
- **Prediction queries** — "When will Bin 1 be ready?" → ML-estimated dates
- **Smooth chat UI** — Bubble interface with bot/user differentiation

---

## 🎨 Design System

| Element | Specification |
|---------|-------------|
| **Color Palette** | Eco-green gradient (#1a3d2b → #2d6a4f) with cream accents |
| **Typography** | DM Sans (body) + Space Grotesk (headings) |
| **Layout** | Mobile-first, 390×844px iPhone frame simulation |
| **Animations** | CSS transitions, smooth screen switching, progress ring SVG |
| **Icons** | Emoji-based semantic icons (🌡️💧🧪💨🤖📡) |

---

## 🚀 Getting Started

### Option 1: Open in Browser (Fastest)
```bash
# Simply open the HTML file in any browser
double-click Project1_CompostIQ_MobileApp.html
```

### Option 2: Local Server (for development)
```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000/Project1_CompostIQ_MobileApp.html
```

### Option 3: On Your Phone
1. **Email/WhatsApp** the HTML file to yourself
2. Open on your phone → tap "Open with Chrome/Safari"
3. **Screen record** the demo for your application!

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | HTML5, CSS3, JavaScript | Mobile UI prototype |
| **Styling** | CSS Variables, Flexbox, Grid | Responsive layout |
| **Charts** | CSS Bar Charts, SVG Progress Ring | Data visualization |
| **Icons** | Native Emoji | Semantic iconography |
| **Fonts** | Google Fonts (DM Sans, Space Grotesk) | Typography |

---

## 🔄 Next Steps: Flutter Migration

This HTML prototype demonstrates the **UI/UX concept** and **feature set**. The production version will be rebuilt in:

```
Flutter (Dart) + Firebase Realtime Database + ESP32 MQTT
```

**Migration roadmap:**
- [ ] Set up Flutter project with `flutter create compostiq`
- [ ] Implement responsive layouts with `flutter_screenutil`
- [ ] Connect to Firebase for real-time sensor data
- [ ] Add MQTT client for ESP32 direct communication
- [ ] Integrate ML model via Flask API
- [ ] Build APK for Android deployment

---

## 📸 Screenshots

### Home Dashboard
![Home](https://github.com/aliibtisam1001/CompostIQ-Mobile-App/blob/main/assets/screenshot-home.jpeg))

### Analytics
![Analytics](https://github.com/aliibtisam1001/CompostIQ-Mobile-App/blob/main/assets/screenshot-analytics.jpeg)

### IoT Devices
![IoT](https://github.com/aliibtisam1001/CompostIQ-Mobile-App/blob/main/assets/screenshot-iot.jpeg)

### AI Chat
![Chat](https://github.com/aliibtisam1001/CompostIQ-Mobile-App/blob/main/assets/screenshot-chat.jpeg)

---

## 🧠 AI Integration

The app connects to a **Python ML backend** (see [Project 2](https://github.com/aliibtisam1001/compostiq-iot-ml-pipeline)) that provides:

- **Compost readiness prediction** — Random Forest model (R² = 0.94)
- **Anomaly detection** — Isolation Forest for sensor outliers
- **Smart recommendations** — Rule-based expert system
- **REST API** — FastAPI endpoints for mobile consumption

---

## 📋 Project Context

This app is part of the **AI + IoT Smart Composting Research Project** at Albukhary International University, focusing on:

- 🏘️ Community-scale composting in **Baling & Sik, Kedah**
- 📡 ESP32 sensor networks for environmental monitoring
- 🤖 AI-driven compost optimization
- 📱 Mobile-first community engagement

---

## 👨‍💻 Author

**Ali Ibtisam**  
Data Science Undergraduate @ AIU  
CGPA: 3.89/4.0 | Fully Funded Scholarship  
📧 aliibtisam1001@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/aliibtisam1001) | [GitHub](https://github.com/aliibtisam1001)

---

## 📄 License

MIT License — feel free to use for educational and research purposes.

---

<p align="center">
  <sub>Built with 💚 for sustainable communities · AIU Research Project 2026</sub>
</p>

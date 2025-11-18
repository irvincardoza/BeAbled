# BeAbled – Where Hands Speak Louder

### 🎉 **Winner of the Google Developer Student Clubs (GDSC) SFU Hackathon 2025** 🎉
BeAbled is an accessibility-focused web application designed to support communication for the Deaf and Hard of Hearing community. The platform uses a custom-built ASL gesture recognition model and converts recognized gestures into synthesized speech in real time.

---






<img width="2130" height="1767" alt="image" src="https://github.com/user-attachments/assets/101cfb91-8f69-44b2-ba5a-722810e5da2b" />


## 🌟 Key Features

- **Real-time ASL Gesture Recognition** powered by a custom MobileNet-based CNN  
- **Speech Generation** using the Web Speech API  
- **Custom-trained model and handcrafted dataset** collected and annotated by our team  
- **Lightweight Flask backend** for fast inference  
- **Clean, intuitive UI** with live prediction overlays  
- **Optional room-based interaction** using Socket.IO (minimal focus)

---
https://github.com/user-attachments/assets/0ef17abf-ba9f-471d-97f4-20a286a7e710



## 🤖 Custom AI Model

- **Model:** `gesture_mobilenet_advanced2.h5`  
- **Labels:** `class_indices.json`  
- **Architecture:** MobileNet backbone with custom classification layers  
- **Dataset:** Fully self-collected ASL gesture dataset  
- **Training:** Designed, trained, and optimized entirely by our team  
- **Performance:** Real-time inference suitable for live webcam input

This project uses no external ASL datasets. Everything was built from scratch for this application.


## 🧠 Tech Stack

**Frontend:** HTML, CSS, Bootstrap, JavaScript  
**Backend:** Python (Flask, Flask-SocketIO)  
**AI/ML:** TensorFlow, MediaPipe, MobileNet  
**Speech:** Web Speech API  
**Camera Input:** WebRTC `getUserMedia()`

---




## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/beabled.git
cd beabled
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the backend
```bash
python app.py
```

### 4. Open the UI
```
http://localhost:5500
```

---
## 💜 Purpose

BeAbled was built to help make communication more accessible for the Deaf and Hard of Hearing community using real-time AI. Our goal is to expand it into a more complete assistive communication tool.

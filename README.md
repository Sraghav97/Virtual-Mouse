<!-- Title with gradient effect -->
<h1 align="center" style="font-weight:bold">
  🖥️✨ Virtual Mouse using Hand Gestures ✨🖱️
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20With-Python%203.7+-blueviolet?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Computer%20Vision-OpenCV-green?style=for-the-badge&logo=opencv" />
  <img src="https://img.shields.io/badge/Hand%20Tracking-MediaPipe-orange?style=for-the-badge&logo=google" />
  <img src="https://img.shields.io/badge/Mouse%20Control-PyAutoGUI-yellow?style=for-the-badge" />
</p>

<p align="center">
  Control your computer with hand gestures using just a webcam and AI 🤯  
  <br><br>
  <strong>No hardware, no touch — just gestures!</strong>
</p>

---

## 🧠 Overview

**Virtual Mouse** is an AI-powered desktop control system that transforms your webcam into a gesture-based mouse. Using **MediaPipe**, **OpenCV**, and **PyAutoGUI**, you can:

- Move the mouse 🖱️
- Click ✨
- Double-click 👆👆
- Take screenshots 📸  
All in real-time — with just your hand!

---

## 🔥 Demo Preview

<p align="center">
  <!-- Replace with your GIF -->
  <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" alt="demo" width="600"/>
</p>

> _Add a real demo GIF to impress even more!_  
> Record using OBS or ScreenRec and upload to GitHub/GIF hosting.

---

## ⚙️ Tech Stack

| Technology     | Description                                      |
|----------------|--------------------------------------------------|
| 🐍 Python      | Programming language for logic & integration     |
| 🖐️ MediaPipe  | Hand tracking & landmark detection               |
| 🎥 OpenCV      | Camera access & video rendering                  |
| 🧠 PyAutoGUI   | Mouse automation with gesture mapping            |
| 📐 NumPy       | Coordinate math & gesture thresholds             |

---

## ✋ Supported Gestures

| Gesture | Action           | Description |
|--------|------------------|-------------|
| 👉     | Mouse Movement    | Move index finger to move cursor |
| 👌     | Left Click        | Index + thumb pinch |
| ✌️     | Screenshot        | Index & thumb closed, others open |
| ❌     | Quit              | Press `q` on your keyboard |

---

## 🛠️ Installation

### 🔧 Requirements
- Python 3.7+
- Webcam (Built-in or USB)

### 📦 Setup

```bash
git clone https://github.com/Sraghav97/virtual-mouse.git
cd virtual-mouse
pip install -r requirements.txt
python main.py

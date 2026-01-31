# GestureSnake 🐍✋

A gesture-controlled Snake game built using **Python, OpenCV, MediaPipe, and Pygame**.  
Control the snake in real time using hand movements captured from your webcam — no keyboard required.

---

## 🎮 Demo
> Demo GIF coming soon  
*(Will be added after gameplay recording)*

---

## ✨ Features

- **Gesture-Based Controls**  
  Control snake movement using hand gestures (UP, DOWN, LEFT, RIGHT).

- **Smooth Snake Logic**  
  Clean and responsive movement with jitter-free gesture handling.

- **Fruit & Score System**  
  Fruits spawn randomly, score increases correctly, and growth is animated.

- **High Score Tracking**  
  High scores are stored locally and auto-updated.

- **Modular Architecture**  
  Clear separation of game logic, rendering, hand tracking, and gesture smoothing.

---

## 🧩 Architecture Overview

src/
├── snake.py # Main game loop and core logic
├── hand_tracker.py # Hand detection using MediaPipe
├── gesture_buffer.py # Gesture smoothing & stabilization
├── renderer.py # Rendering, animations, UI


Each module has a single responsibility, making the project easy to extend and maintain.

---

## 🛠️ Tech Stack

- **Python 3.11**
- **Pygame** – game loop & rendering
- **OpenCV** – camera input
- **MediaPipe** – real-time hand tracking

---

## 🚀 Installation & Run

Clone the repository:
```bash
git clone https://github.com/mihika-devops/GestureSnake.git
cd GestureSnake
Create and activate a virtual environment (recommended):

python -m venv venv
source venv/bin/activate   # macOS / Linux
Install dependencies:

pip install -r requirements.txt
Run the game:

python src/snake.py
🎯 Controls
Move hand up → Snake moves up

Move hand down → Snake moves down

Move hand left → Snake moves left

Move hand right → Snake moves right

Closed fist → Pause (if enabled)

⚠️ Notes
Requires a working webcam

Designed for local execution (camera-based projects cannot run on GitHub Pages)

📌 Project Status
Actively improving:

Demo GIF

Visual polish

Gesture accuracy tuning

👤 Author
Mihika Bhosale
Computer Vision & Python Projects


---

## 📤 Final step: commit it
Run:
```bash
git add README.md
git commit -m "Improve README documentation"
git push

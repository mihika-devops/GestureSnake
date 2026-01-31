# Gesture Snake (Pro)

![Python](https://img.shields.io/badge/python-3.11-blue)
![OpenCV](https://img.shields.io/badge/opencv-4.x-brightgreen)
![MediaPipe](https://img.shields.io/badge/mediapipe-0.10-orange)

A **gesture-controlled Snake game** built with **Python**, **OpenCV**, and **MediaPipe**.  
Move the snake using your hand and enjoy a fully interactive experience without a keyboard!

---

## 🎮 Features

- **Gesture Controls:** Move the snake using hand gestures (UP, DOWN, LEFT, RIGHT). Pause with a closed fist.
- **Smooth Snake Logic:** Snake movement handled by a dedicated `Snake` class; responsive and jitter-free.
- **Fruit Pop Animation:** Fruits grow/shrink when eaten; score increments properly.
- **High Score Tracking:** Scores saved in `highscore.txt` and auto-updated.
- **Modular Architecture:** Clean separation of game logic, rendering, hand detection, and gesture smoothing.

---


## ⚡ Installation

1. Clone the repository:

```bash
git clone https://github.com/<username>/<repo>.git
cd GestureSnake
Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # macOS/Linux
# or
venv\Scripts\activate      # Windows
Install dependencies:

pip install mediapipe opencv-python numpy
▶️ Running the Game
python src/snake_game.py
Controls:

Hand Gestures: Move the snake.

Fist: Pause the game.

SPACE: Start/restart the game.

ESC: Quit the game.

🗂 Folder Structure
GestureSnake/
│
├─ src/
│   ├─ snake_game.py
│   ├─ vision/
│   │   └─ hand_tracker.py
│   ├─ game/
│   │   └─ snake.py
│   ├─ utils/
│   │   └─ gesture_buffer.py
│   ├─ ui/
│   │   └─ renderer.py
│   └─ assets/
│       └─ apple.png
├─ screenshots/
│   └─ start.png, gameplay.png, gameover.png
├─ venv/
└─ README.md



💡 Notes
Make sure your webcam is free and accessible.

Gestures are based on index finger position — keep hand in front of camera.

Designed for single-hand use.


## 📜 License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.


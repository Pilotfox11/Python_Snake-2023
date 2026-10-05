# Python_Snake-2023
Classic Snake and Tetris games built with Python &amp; Pygame. Heavily commented and optimized for beginners to learn game development logic.

# 🐍🧱 Classic Pygame Projects: Snake & Tetris

Welcome! This repository contains my early game development projects built with **Python** and **Pygame**. 

Originally created as a school project, this code is heavily commented and structured to be **highly educational for beginners**. If you are just starting with game development, this is a great place to see how game loops, collision detection, and Object-Oriented Programming (OOP) work in practice.

## ✨ Key Features

### 🐍 Snake
- **Gradient Rendering:** The snake's body features a smooth RGB color gradient from head to tail.
- **Seamless Wall Wrapping:** Uses modulo arithmetic (`%`) for clean and bug-free screen edge crossing.
- **Input Buffering:** Prevents the classic "suicide bug" (turning 180 degrees instantly) by tracking the `last_direction`.
- **Dynamic Spawning:** Ensures food never spawns inside the snake's body.

### 🧱 Tetris
- **Clean OOP Architecture:** Separation of concerns between `GameLogic` (rules, state) and `App` (rendering, events).
- **Delta Time (`dt`):** Frame-independent movement, ensuring the game runs at the same speed on all computers.
- **Matrix Rotation:** Custom implementation of piece rotation using coordinate mapping.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Library:** Pygame
- **Extras:** NumPy (used in Tetris for matrix rotation)

🎓 Why this code is great for beginners
Unlike many minimalist tutorials, this code includes:
Detailed inline comments explaining the "why" behind the logic, not just the "what".
Proper class separation (App vs GameLogic), teaching good software design habits early on.
Edge-case handling (like preventing food from spawning on the snake).
Feel free to fork this repository, modify the code, and use it as a foundation for your own games!
📜 License
This project is open-source and available under the MIT License

# 🏎️ 2D Car Game – Investigative Project Report

## 🔗 Project Repository  
**[2D Car Game on GitHub](https://github.com/md-rubel/2D-Car-Game-OpenGL)**

---

## 👤 Project Information

- **Course:** DSA Lab  
- **Semester:** Winter 2025  
- **Institution:** DAIICT  

---

## 📌 Project Objective

To analyze and understand the core logic and structure of a 2D car racing game implemented using **C++** and **OpenGL**, focusing on:

- 2D rendering techniques  
- Real-time input handling  
- Basic collision detection  
- Scoring and level system

---

## 🛠️ Technologies Used

| Tool/Technology     | Description                      |
|---------------------|----------------------------------|
| Language            | C++                              |
| Graphics Library    | OpenGL (via FreeGLUT)            |
| Development Environment | VS Code + MinGW (Windows)    |
| Sound API           | Windows Multimedia API (PlaySound) |

---

## 🎮 Gameplay Summary

- Control a **green car** using arrow keys.
- Avoid **oncoming traffic** while the game speed increases over time.
- The road is animated with divider lines to simulate forward movement.
- A **collision ends the game**, and the final **score** is displayed.

---

## 📷 Screenshots

> _(Add actual screenshots here if available)_

- **In-Game:**  
  _Gameplay showcasing car movement and obstacles_

- **Game Over Screen:**  
  _Display after a collision occurs_

---

## 📐 Core Features and Concepts

| Feature            | Description                                         |
|--------------------|-----------------------------------------------------|
| **Car Movement**   | Controlled via Left/Right arrow keys                |
| **Speed Control**  | Increased/Decreased using Up/Down arrow keys        |
| **Collision Detection** | Uses axis-aligned bounding boxes (AABB)     |
| **Scoring System** | Score increases with time; levels every 50 points   |
| **Game Over Logic**| Triggered by a collision with an enemy car          |
| **Sound Effects**  | Background car sound using `car.wav`                |
| **Graphics**       | Drawn using OpenGL primitives (`glBegin`, `glVertex2f`) |

---

## 🔍 Code Structure Overview

| File       | Purpose                                                            |
|------------|--------------------------------------------------------------------|
| `main.cpp` | Contains the **game loop**, **rendering**, **input handling**, and **state management** |

### Key Functions:

- `startGame()` – Handles gameplay rendering loop  
- `fristDesign()` – Displays the start/menu screen  
- `display()` – Main OpenGL display handler  
- `spe_key()` & `processKeys()` – Handle user keyboard input  
- `collision()` – Detects car-to-car collisions  
- `PlaySound()` – Plays background car engine sound  

---

## ⚙️ Build & Run Instructions

### ✅ Requirements:

- C++ Compiler (e.g., g++ via MinGW)  
- FreeGLUT installed  
- `car.wav` file in the same directory  

### 🔧 Compilation (Command Line):

```bash
g++ main.cpp -o car-game.exe -lopengl32 -lglu32 -lfreeglut -lwinmm
```

### 🚀 Run the Game:

```bash
./car-game.exe
```

> ⚠️ Make sure `car-game.exe`, `car.wav`, and all assets are in the **same folder**.

---

## 📈 Observations & Learnings

- Gained hands-on experience rendering 2D graphics using OpenGL.
- Learned about real-time game loops and input event handling.
- Explored simple scoring systems and collision mechanics.
- Understood how global flags and states control the game flow.

---

## 🔄 Scope for Improvement

- Refactor into **Object-Oriented Design** with classes for cars and obstacles.
- Replace global variables with better encapsulation.
- Add visual effects like skid trails, explosions, etc.
- Introduce power-ups, additional enemy cars, or levels.
- Port to a **cross-platform game library** like SFML or SDL for portability.

---

## 🙏 Credits

- **Original Project:** [MD Rubel's GitHub Repository](https://github.com/md-rubel/2D-Car-Game-OpenGL)  
- **Investigated By:**
  - Marm Bhatt – 202401408  
  - Kuldeep Solanki – 202404040  
  - Raj Sutariya – 202401221  
  - Harsh Patel – 202401261  
  - Harshil Tejot – 202401265

---

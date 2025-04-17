# 🚗 2D Car Racing Game

A simple 2D car racing game developed in C++ using OpenGL. The player controls a green car, avoiding incoming traffic on a highway to score points and level up.

![Gameplay Screenshot](./Screenshot1.png)
![Game Over Screen](./Screenshot2.png)

---

## 🧩 Features

- Simple keyboard-controlled gameplay.
- Increasing difficulty based on score and level.
- Real-time speed and score display.
- Game over detection with final score screen.
- Sound effects (requires `car.wav` in the root directory).

---

## 🎮 How to Play

| Key       | Action                  |
|-----------|--------------------------|
| `↑`       | Increase Speed            |
| `↓`       | Decrease Speed            |
| `←`       | Move Left                 |
| `→`       | Move Right                |
| `SPACE`   | Start the Game            |
| `ESC`     | Exit                      |

Avoid crashing into other cars. The game ends if a collision occurs.

---

## 🖥️ Screenshots

### In-Game

![In-Game](./Screenshot1.png)

### Game Over Screen

![Game Over](./Screenshot2.png)

---

## ⚙️ Installation & Run Instructions

### Prerequisites

- C++ Compiler (e.g., `g++` from MinGW)
- OpenGL & FreeGLUT Libraries
- Windows OS (uses `windows.h`, `winmm.lib`)

### Setup (for VSCode with MinGW)

1. Clone this repository or download the source files.
2. Place your sound file (`car.wav`) in the project root directory.
3. Make sure your `tasks.json` in VSCode is set up as follows:

```json
{
  "version": "2.0.0",
  "tasks": [
    {
      "label": "Build and Run Car Game",
      "type": "shell",
      "command": "g++",
      "args": [
        "main.cpp",
        "-o",
        "car-game.exe",
        "-lopengl32",
        "-lglu32",
        "-lfreeglut",
        "-lwinmm"
      ],
      "group": {
        "kind": "build",
        "isDefault": true
      },
      "problemMatcher": []
    }
  ]
}

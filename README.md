📝 2D Car Game – Investigative Project Report
🔗 Project Repository
2D Car Game on GitHub

👤 Project
Course: DSA Lab 
Semester: Winter 2025
Institution: DAIICT

📌 Project Objective
To analyze and understand the core logic and structure of a 2D car racing game implemented using C++ and OpenGL, with an emphasis on rendering techniques, real-time input handling, basic collision detection, and scoring systems.

🛠️ Technologies Used
Language: C++

Graphics Library: OpenGL (via FreeGLUT)

Development Environment: VS Code + MinGW (on Windows)

Sound API: Windows Multimedia API (PlaySound)

🎮 Gameplay Summary
The player controls a green car that must avoid oncoming vehicles while the speed increases over time. The road is animated using divider strips to simulate movement. The game ends when a collision occurs, and the score is displayed.

📷 Game Screenshots
In-Game:

Game Over:

📐 Core Concepts and Features

Feature	Description
Car Movement	Controlled using left/right arrow keys
Speed Control	Increase/decrease using up/down arrow keys
Collision Detection	Axis-aligned bounding box check
Scoring & Levels	Score increases over time; level changes every 50 points
Game Over Logic	Triggered by collision
Sound Effects	Background sound using car.wav
Graphics Rendering	Manual polygon drawing using glBegin() / glVertex2f()
🔍 Code Structure Overview
main.cpp: Contains the full game loop, rendering logic, input handling, and state management.

Functions include:

startGame() – Main game loop and rendering logic.

fristDesign() – First screen layout (intro/menu).

display() – OpenGL display function.

spe_key() and processKeys() – Keyboard event handlers.

collision() – Collision detection logic.

PlaySound() – Handles looping car sound.

⚙️ Build & Run Instructions
✅ Requirements:
C++ compiler (e.g., g++ via MinGW)

FreeGLUT library installed

car.wav sound file in the same directory

🔧 Compilation (Command Line):
bash
Copy
Edit
g++ main.cpp -o car-game.exe -lopengl32 -lglu32 -lfreeglut -lwinmm
🚀 Run the Game:
bash
Copy
Edit
./car-game.exe
Make sure the executable, car.wav, and all resources are in the same directory.

📈 Observations & Learnings
Learned how to render 2D objects using OpenGL primitives.

Understood how basic game loops, real-time rendering, and keyboard input work in OpenGL.

Investigated how scoring and difficulty scaling can be implemented.

Observed the role of state variables and global flags in controlling gameplay.

🔄 Scope for Improvement
Use OOP design to manage game objects like cars and road elements.

Replace global variables with encapsulated classes.

Add more visual effects, power-ups, and enemy types.

Introduce smoother collision physics and hitbox logic.

Port the code to cross-platform frameworks like SFML or SDL.

🙏 Credits
Original Project: MD Rubel's GitHub Repo

Investigated by: 
1. Marm Bhatt - 202401408
2. Kuldeep Solanki - 202404040
3. Raj Sutariya - 202401221
4. Harsh Patel - 202401261
5. Harshil Tejot - 202401265

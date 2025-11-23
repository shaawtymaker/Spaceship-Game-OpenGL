🚀 Spaceship Shooting Game — OpenGL (C / C++)

A classic 2D Space Shooter Game built using OpenGL (FreeGLUT) in C/C++.
Dodge incoming objects, shoot them down, survive as long as possible, and beat the high score!

🎮 Game Description
********************************************************************
**                     G A M E   D E S C R I P T I O N S          **
**                                                                 **
**   Keyboard Controls:   W, A, S, D                               **
**   Mouse: Left-click to fire                                     **
**                                                                 **
**   INSTRUCTIONS:                                                 **
**       - Dodge falling objects                                   **
**       - Shoot them down                                         **
**                                                                 **
**   OBJECTIVE:                                                    **
**       - Beat the High Score                                     **
**       - +1 point per object destroyed                           **
**       - +50 points every level up                               **
********************************************************************


The game also stores your highest score in:

HighScoreFile.txt

📦 Requirements

You must have the following installed:

g++ / MinGW

OpenGL

FreeGLUT

GLU

(Windows users typically install freeglut and place .dll files next to the executable.)

🛠️ Building the Game
1️⃣ Clone the repository
git clone https://github.com/shaawtymaker/Spaceship-Game-OpenGL.git

2️⃣ Navigate to the project folder
cd Spaceship-Game-OpenGL

3️⃣ Compile the game
g++ spaceship_fixed.cpp -o spaceship.exe -lfreeglut -lopengl32 -lglu32


(You must run this from inside the project directory.)

4️⃣ Run the game
./spaceship.exe

🎯 Gameplay Features

Smooth spaceship movement

Mouse-aimed laser shooting

Multiple asteroid types

Increasing difficulty with speed scaling

Level progression system

High score saving

Game over + restart screen

Instructions screen & menu UI

📁 File Structure
Spaceship-Game-OpenGL/
│
├── spaceship_fixed.cpp      # Main game source code
├── HighScoreFile.txt        # Auto-generated high score file
├── README.md                # This file
└── (DLLs for FreeGLUT if needed)

📝 Notes

If HighScoreFile.txt doesn’t exist, the game will create it automatically.

On first run, the high score is set to 0.

Ensure FreeGLUT .dll files are in the same directory as the executable.

⭐ Credits

This project was built for an OpenGL / Computer Graphics mini-project and showcases classic immediate-mode OpenGL rendering techniques combined with interactive keyboard and mouse handling.

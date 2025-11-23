🚀 Spaceship Shooting Game — OpenGL (C/C++)

A classic 2D Space Shooter built using OpenGL (FreeGLUT) in C/C++.
Dodge incoming objects, shoot them down, survive, and beat the high score!

🎮 Game Description
********************************************************************
**                     G A M E   D E S C R I P T I O N S          **
**                                                                 **
**   Keyboard Controls:   W, A, S, D                               **
**   Mouse Input:         Left-click to fire laser                 **
                                                                
**   INSTRUCTIONS:                                                 **
**       - Dodge incoming objects                                  **
**       - Shoot objects to earn points                            **
                                                               
**   OBJECTIVE:                                                    **
**       - Beat the high score                                     **
**       - +1 point per object destroyed                           **
**       - +50 points per level up                                 **
********************************************************************


High score is automatically saved in:

HighScoreFile.txt

## 📦 Requirements

Make sure you have:

- g++ / MinGW (Windows)

- OpenGL

- FreeGLUT

- GLU

FreeGLUT .dll files must be placed next to the executable on Windows.

```sh
# Step 1: Clone the repository using the project's Git URL. 
git clonehttps://github.com/shaawtymaker/Spaceship-Game-OpenGL.git

# Step 2: Navigate to the project directory. 
cd Spaceship-Game-OpenGL 

# Step 3: open termial in the project directory and run 
g++ spaceship_fixed.cpp -o spaceship.exe -lfreeglut -lopengl32 -lglu32 

# Step 4: run the .exe file 
./spaceship.exe
```

## 🎯 Key Features

- Smooth spaceship movement

- Mouse-aim laser system

- Multiple asteroid shapes

- Increasing difficulty

- Level progression

- Game Over & Restart screens

- High score persistence

- Clean UI (Start / Instructions / Quit)

## 📁 Folder Structure
Spaceship-Game-OpenGL/
│
├── spaceship_fixed.cpp        # Main game source file
├── HighScoreFile.txt          # Auto-generated high score file
├── README.md                  # Project readme
└── (DLLs for FreeGLUT if needed)

## 📝 Notes

The game creates HighScoreFile.txt automatically if missing.

FreeGLUT .dll is required to run the .exe on Windows.

You can recompile the game anytime using the g++ command shown above.

## ⭐ Credits

Built as a Computer Graphics / OpenGL Mini-Project.
Showcases classic OpenGL immediate-mode rendering + basic game logic.

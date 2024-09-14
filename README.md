# Paddle Smash

**Paddle Smash** is a simple 2-player game based on the classic Ping Pong game. This project was developed using **C++** with **OpenGL** as part of a Computer Graphics mini-project for the 6th semester of the **Bachelor of Engineering** program in **Computer Science and Engineering**.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Play](#how-to-play)
- [System Requirements](#system-requirements)
- [Contributors](#contributors)

## Introduction
**Paddle Smash** is an interactive 2-player game where each player controls a paddle to hit the ball and prevent it from passing their side. Points are awarded whenever the opponent misses the ball. The first player to reach 5 points is declared the winner. Paddle movement is controlled via the keyboard, making the game interactive and engaging.

The project utilizes **OpenGL** for rendering and game logic, with all coding implemented in **C++**.

## Features
- Two-player mode
- Keyboard-controlled paddle movement
- Random serve at the start of each round
- Score tracking for both players
- The first player to 5 points wins

## Technologies Used
- **C++** for coding
- **OpenGL** for graphics rendering and input handling


## Requirements
- A C++ compiler
- OpenGL and GLUT libraries installed

## Installation and Compilation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/paddle-smash.git
2. Install OpenGL and GLUT libraries:
   ```bash
   sudo apt-get install freeglut3-dev
3. Compile the program:
   ```bash
   g++ -o paddle_smash paddle_smash.cpp -lGL -lGLU -lglut
4. Run the game:
   ```bash
   ./paddle_smash

## How to Play
Player 1 controls the left paddle with W (move up) and S (move down).
Player 2 controls the right paddle using the Up Arrow (move up) and Down Arrow (move down).
The game begins with a random ball serve to either player.
A point is awarded to a player whenever the opponent misses the ball.
The first player to score 5 points wins.

## System Requirements
Hardware: Standard PC with OpenGL-compatible graphics
Software:
- C++ Compiler (e.g., GCC)
- OpenGL and GLUT libraries

## Contributors
Sahithi Srujana C (1JS21CS122)
Pinni Raga Sruthi (1JS21CS102)

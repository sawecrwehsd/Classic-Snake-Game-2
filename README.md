# 🐍 Snake Game

A classic Snake Game where you control the snake, eat apples to grow longer, and increase your score. Avoid hitting the walls and yourself!

## 📌 Overview

This project is a simple implementation of the classic Snake Game. The player controls a continuously moving snake using keyboard controls. The objective is to collect apples, increase the score, and grow the snake while avoiding collisions with the game boundaries and the snake's own body.

The game combines basic game logic, keyboard input handling, collision detection, score tracking, and dynamic movement to recreate the traditional Snake experience.

## 🎮 Gameplay

The objective of the game is straightforward:

* Control the snake around the game area.
* Eat the apples that appear on the screen.
* Each apple increases the player's score.
* Eating an apple also makes the snake longer.
* Avoid hitting the walls.
* Avoid colliding with the snake's own body.
* Continue playing to achieve the highest possible score.

## ✨ Features

* 🐍 Classic Snake gameplay
* 🍎 Apple-based scoring system
* 📈 Increasing score
* 📏 Snake growth after eating apples
* 🎮 Keyboard-based movement
* 💥 Wall collision detection
* 💥 Self-collision detection
* 🔄 Continuous snake movement
* 🏆 High-score gameplay concept
* 🖥️ Simple and easy-to-understand game structure

## 🕹️ Controls

| Key            | Action     |
| -------------- | ---------- |
| ⬆️ Up Arrow    | Move Up    |
| ⬇️ Down Arrow  | Move Down  |
| ⬅️ Left Arrow  | Move Left  |
| ➡️ Right Arrow | Move Right |

## 🧠 Game Logic

The game operates through a continuous gameplay loop:

1. The snake moves in its current direction.
2. The game checks the snake's new position.
3. If the snake reaches an apple, the score increases.
4. The snake grows after eating the apple.
5. A new apple is generated at another position.
6. The game checks for collisions.
7. If the snake hits a wall or itself, the game ends.
8. The process continues until a collision occurs.

## 🍎 Scoring System

The score represents the number of apples successfully collected during the game.

Each time the snake eats an apple:

```text
Score = Score + 1
```

As the snake grows longer, avoiding collisions becomes increasingly challenging.

## 💥 Collision Detection

The game includes two main types of collision detection:

### Wall Collision

The game detects when the snake reaches the boundaries of the playable area. Hitting a wall ends the game.

### Self Collision

The game also checks whether the snake's head touches any part of its own body. If this happens, the game ends.

## 🔄 Game Flow

```text
Start Game
    ↓
Snake Begins Moving
    ↓
Player Controls Snake
    ↓
Snake Finds Apple?
   /        \
 Yes        No
  ↓          ↓
Increase    Continue
Score       Moving
  ↓
Grow Snake
  ↓
Generate New Apple
    ↓
Check Collision
    ↓
Collision?
 /        \
Yes        No
 ↓          ↓
Game Over  Continue
```

## 🛠️ Technologies

The project is built as a lightweight game implementation and focuses on fundamental programming concepts such as:

* Game loops
* Keyboard input
* Conditional logic
* Variables and data handling
* Collision detection
* Coordinate-ba

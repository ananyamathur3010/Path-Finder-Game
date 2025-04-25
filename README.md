# Path-Finder-Game
A dynamic grid-based puzzle game with movement logic and obstacles.
# 🧭 Path Finder Game

A dynamic, interactive 10x10 grid-based puzzle game built with **React.js**, where the player must find a path from Start (S) to End (E), avoiding randomly placed obstacles (X) while following strict movement rules.

## 🎯 Features

- **Randomized 10x10 Grid** with Start, End, and at least 30% Obstacles
- **Player Movement Rules**:
  - Move only Up, Down, Left, or Right
  - No diagonal movement or backtracking
  - Cannot move through obstacles
- **Real-time UI Updates** with clear visual cues
- **Win Condition**: Reach the End tile
- **Lose Condition**: No valid moves remaining

## 🌟 Bonus Features

- ⏱️ **Timer Mode**: Reach the End within 60 seconds
- ↩️ **Undo Move**: Step back one move
- 🧮 **Scoring System**: Fewer moves = higher score
- 🔄 **Randomized Grid**: New layout each game

## 🛠️ Tech Stack

- **React.js** (Functional Components + Hooks)
- **TailwindCSS** for UI styling
- **JavaScript (ES6+)**

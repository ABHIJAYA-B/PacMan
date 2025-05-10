# 🟡 Java Pacman Game

This is a custom-built clone of the classic **Pacman** arcade game, developed in **Java** using **Swing** and **AWT** for graphics and keyboard input. The game features animated ghosts, pellet collection, scoring, and lives tracking in a grid-based maze.

## 🎮 Features

- Fully playable Pacman game with:
  - Smooth character movement
  - Four animated ghosts (blue, red, orange, pink)
  - Pellet collection system with scoring
  - Lives system and game over state
- Automatic maze rendering using a tile map
- Simple AI logic for ghost movement
- Game restart on key press after game over

## 🧠 Technologies Used

- **Java**
- **Java Swing** (for UI components and painting)
- **AWT** (for keyboard event handling)
- **OOP** principles (custom `Block` class for entities)

## 🗺️ Game Map

The map is defined using a 2D array with symbolic characters:
- `X`: Wall
- `P`: Pacman starting position
- `b`, `o`, `p`, `r`: Ghosts (blue, orange, pink, red)
- ` ` (space): Pellet
- `O`: Skip tile (empty path)

## 📦 Installation & Running

1. Clone the repository or copy the source files into a Java project:
   ```bash
   git clone https://github.com/your-username/java-pacman.git
   cd java-pacman

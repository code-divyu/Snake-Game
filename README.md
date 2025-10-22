# Snake Game 🐍

A classic Snake game implementation built with Java Swing. Guide the snake to eat food, grow longer, and avoid collisions!

## 📋 Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Classic Gameplay**: Experience the traditional Snake game mechanics
- **Smooth Controls**: Responsive keyboard controls using arrow keys
- **Score Tracking**: Keep track of your current score
- **Game Over Detection**: Collision detection with walls and self
- **Clean UI**: Simple and intuitive graphical interface
- **Restart Functionality**: Easy game restart after game over

## 🎮 How to Play

1. **Start the Game**: Run the application to begin playing
2. **Control the Snake**: 
   - ⬆️ **Up Arrow**: Move up
   - ⬇️ **Down Arrow**: Move down
   - ⬅️ **Left Arrow**: Move left
   - ➡️ **Right Arrow**: Move right
3. **Objective**: 
   - Guide the snake to eat the food (dots)
   - Each food eaten increases your score and snake length
   - Avoid hitting the walls or the snake's own body
4. **Game Over**: The game ends when the snake collides with walls or itself

## 🚀 Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Any Java IDE (Eclipse, IntelliJ IDEA, NetBeans) or command line

### Installation & Running

#### Option 1: Using an IDE
1. Clone this repository:
   ```bash
   git clone https://github.com/code-divyu/Snake-Game.git
   ```
2. Open the project in your preferred Java IDE
3. Navigate to `src/snakegame/SnakeGame.java`
4. Run the `SnakeGame.java` file

#### Option 2: Command Line
1. Clone this repository:
   ```bash
   git clone https://github.com/code-divyu/Snake-Game.git
   cd Snake-Game
   ```
2. Compile the Java files:
   ```bash
   javac -d . src/snakegame/*.java
   ```
3. Run the game:
   ```bash
   java snakegame.SnakeGame
   ```

## 📁 Project Structure

```
Snake-Game/
├── src/
│   └── snakegame/
│       ├── SnakeGame.java    # Main class - Entry point of the application
│       └── Board.java        # Game logic and UI implementation
├── nbproject/                # NetBeans project files
├── build.xml                 # Build configuration
├── manifest.mf               # Manifest file
└── README.md                 # Project documentation
```

## 🔧 Technologies Used

- **Java**: Core programming language
- **Swing**: GUI framework for the user interface
- **AWT**: Abstract Window Toolkit for graphics and event handling
- **NetBeans**: IDE project structure (optional)

## 🎯 Game Mechanics

- **Snake Movement**: Continuous movement in the current direction
- **Food Generation**: Random food placement on the game board
- **Collision Detection**: Checks for wall and self-collision
- **Score System**: Points awarded for each food item consumed
- **Game Loop**: Timer-based game updates for smooth gameplay

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions:
- Add sound effects
- Implement different difficulty levels
- Add high score persistence
- Create different themes/skins
- Add multiplayer functionality
- Implement power-ups

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🏆 Acknowledgments

- Inspired by the classic Nokia Snake game
- Built as a learning project to demonstrate Java Swing capabilities

## 📞 Contact

**Divyansh** - [@code-divyu](https://github.com/code-divyu)

Project Link: [https://github.com/code-divyu/Snake-Game](https://github.com/code-divyu/Snake-Game)

---

**Enjoy the game! 🎮**  

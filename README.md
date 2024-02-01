# FlappyBird
FlappyBird Game code using Java Programming and OOP Concepts

# Flappy Bird Game

A simple implementation of the classic Flappy Bird game in Java using Swing.

## Overview

This project creates a basic version of the Flappy Bird game using Java Swing. The game consists of a bird that the player controls, and the objective is to navigate the bird through a series of pipes by tapping the spacebar to make the bird jump.

## Features

- **Bird Movement:** The bird moves vertically based on gravity and player input.
- **Pipes:** Pipes are generated at regular intervals, and the player must navigate the bird through the gaps between them.
- **Score Tracking:** The player earns points by passing through the pipes.
- **Game Over:** The game ends if the bird collides with a pipe or falls off the screen.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed

### Running the Game

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/flappy-bird-java.git
    cd flappy-bird-java
    ```

2. Compile the Java files:

    ```bash
    javac FlappyBird.java App.java
    ```

3. Run the game:

    ```bash
    java App
    ```

4. Use the spacebar to control the bird. Press space to start and jump.

## Code Structure

- **FlappyBird.java:** Contains the main game logic, including the bird and pipes' movement, collision detection, and rendering.
- **App.java:** The main class that initializes the JFrame and starts the game.

## Acknowledgments

- This project is inspired by the original Flappy Bird game created by Dong Nguyen.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or improvements, feel free to open an issue or submit a pull request.


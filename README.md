# BlackJack Game

## Overview

This is a simple console-based BlackJack game implemented in Java. Players compete against the house, trying to get as close to 21 points as possible without exceeding it. The game allows players to choose whether to hit (draw another card) or stand (end their turn).

## Features

- Player vs. House gameplay.
- Draw cards randomly from a standard deck.
- Basic scoring system with win, loss, and tie tracking.
- Option to play multiple rounds.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- An IDE or text editor (e.g., IntelliJ IDEA, Eclipse, Visual Studio Code)

### Installation

1. Clone the repository or download the code files.
2. Open the project in your IDE.
3. Ensure all classes are located in the `src` directory.

### Running the Game

1. Compile the Java files:

   ```bash
   javac src/*.java
   ```

2. Run the main class:

   ```
   java src.BlackJack
   ```

### How to Play

1. Upon starting the game, the house and the player will each draw two cards.
2. The player can choose to hit (draw another card) or stand (end their turn).
3. If the player's total exceeds 21, they bust and lose the round.
4. The house will draw cards until it has at least 17 points.
5. The round results will be displayed, indicating whether the player or the house won, or if it was a tie.
6. After each round, the player can choose to play again or exit.

### Code Structure

- BlackJack.java: Main game logic and user interface.
- Card.java: Represents a single playing card with a value and suit.
- Deck.java: Manages the card drawing process from a virtual deck.

### Acknowledgments

- The game implements basic rules of BlackJack. The code is intended for educational purposes to demonstrate object-oriented programming concepts in Java.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

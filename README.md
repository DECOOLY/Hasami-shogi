# Hasami Shogi

A Java-based implementation of the traditional Japanese board game Hasami Shogi, developed as a Grade 11 computer science summative project. This project features a 9x9 grid system, capture tracking, and a graphical user interface (GUI) built with Java Swing.

## Features
* **Game Modes**: Supports both Player vs. Player (PvP) and Player vs. Computer (PvC) modes.
* **Dual Interface**: Includes both a terminal-based interface and a functional GUI.
* **Capture Logic**: Implements complex capture mechanics, including horizontal, vertical, and corner-trap detection.
* **Robust Architecture**: Built with a modular, object-oriented design for maintainability and scalability.

## Project Structure
The project is organized into the following components:
* `board.java`: Handles the 9x9 grid logic and movement validation.
* `position.java`: Manages coordinate abstraction and validation.
* `GameEngine.java`: Controls game state, turn order, and win conditions.
* `computer.java`: Contains the AI logic for computer-controlled moves.
* `GUI.java`: Manages the visual interface and user interaction.
* `test_new.java`: Includes unit tests for verifying game logic and boundary checks.

## Getting Started
1. Clone the repository.
2. Compile the files: `javac *.java`
3. Run the GUI application: `java GUI`

## Testing
The project includes a dedicated `test_new.java` suite to validate game rules, movement constraints, and edge cases, ensuring the game logic is robust and error-free.

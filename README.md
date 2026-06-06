# 2048_Game_Python-Tkinter
A modular 2048 game clone built using Python, Tkinter, and Object-Oriented Programming (OOP) principles.

A desktop clone of the classic 2048 puzzle game, built entirely in Python using the Tkinter library for the graphical user interface. 

This project demonstrates core software engineering principles, specifically using Object-Oriented Programming (OOP) to cleanly separate the backend game logic from the frontend UI.

## 🎮 Features
* **Modular Architecture:** Core matrix manipulation and game state logic are isolated from the Tkinter GUI.
* **Algorithmic Tile Merging:** Implements 2D array transformations for dynamic tile shifting, merging, and randomized generation.
* **Interactive UI:** Real-time visual updates and custom color-mapping based on tile values.
* **State Management:** Automatic detection of win (reaching the 2048 tile) and loss (no valid moves remaining) states.

## ⚙️ Prerequisites
To run this game, you only need Python installed on your system. Tkinter is included in the standard Python library, so no external dependencies are required.
* Python 3.x

## 🚀 How to Run
1. Clone this repository to your local machine:
    ```bash
           git clone https://github.com/ZenoWalker/2048_Game_Python-Tkinter.git
2. Navigate to the project directory:
   ```bash
           cd 2048-Python-Tkinter
   
3. Run the main executable file:
   ```bash
           python main.py
  (Note: Depending on your system, you might need to use python3 main.py)

**📂 Project Structure:**

main.py: Handles the frontend. It initializes the Tkinter window, binds keyboard events, maps colors, and updates the grid visuals.

game.py: Handles the backend. It contains the Game class, which manages the 4x4 2D list, calculates movements (Up, Down, Left, Right), and validates game states.

**⌨️ Controls:**

W - Move Up

S - Move Down

A - Move Left

D - Move Right

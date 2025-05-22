# UnbeatableTicTacToe-Pygame

Welcome to **UnbeatableTicTacToe-Pygame** — a slick, interactive Tic Tac Toe game powered by Python and Pygame, featuring an AI opponent that uses the Minimax algorithm. Play against a bot that’s literally impossible to beat (unless you settle for a draw). This is Tic Tac Toe, leveled up with graphics, sound, and smarts.

---

## Features

- **Unbeatable AI** powered by the Minimax algorithm  
- Graphical board rendered with Pygame (no more boring console!)  
- Two game modes: Player vs Player (PvP) and Player vs AI  
- Dynamic, clear win detection with animated winning lines  
- Easy controls: click to place your mark, keyboard shortcuts for quick actions  
- AI difficulty levels: from random moves to strategic perfection  
- Restart and mode-switching on the fly with keyboard keys

---

## How to Play

- Launch the game and watch the board appear.  
- Click on any empty square to place your mark (X or O).  
- Your goal: get three marks in a row — vertically, horizontally, or diagonally.  
- The AI will respond with its move if you're playing against it.  
- Use these keyboard shortcuts to control the game:
  - `G` — Toggle between Player vs Player and Player vs AI modes  
  - `R` — Restart the game  
  - `0` — Set AI to random moves (easy mode)  
  - `1` — Set AI to unbeatable Minimax mode (hard mode)  
- Watch the winning line get drawn when someone wins, or settle for a draw.

---

## How It Works

- The game uses a **Board** class to track the game state and check wins.  
- The **AI** class implements the Minimax algorithm — it simulates every possible move recursively to pick the absolute best one.  
- The game runs on **Pygame**, rendering the grid, X's, and O's, and capturing mouse and keyboard inputs.  
- Minimax ensures the AI never loses; if you can beat it, you’ve basically cracked the code.

---

## Tech Stack

- **Python 3.x** — Core language for logic and game flow  
- **Pygame** — For rendering graphics and handling user input  
- **NumPy** — For efficient board state management  
- **Minimax Algorithm** — The unbeatable AI decision-making engine  

---

## Installation & Running

1. Clone this repo:
    ```bash
    git clone https://github.com/Harshil-Madaan/UnbeatableTicTacToe-Pygame.git
    ```
2. Navigate to the folder:
    ```bash
    cd UnbeatableTicTacToe-Pygame
    ```
3. Make sure you have Python 3.x installed. Then install Pygame and NumPy if you haven’t yet:
    ```bash
    pip install pygame numpy
    ```
4. Run the game:
    ```bash
    python your_main_file_name.py
    ```
   *(Replace `your_main_file_name.py` with the actual Python script filename you run — e.g., `main.py`)*

---

## Controls Summary

| Key/Button | Action                            |
|------------|---------------------------------|
| Mouse Click| Place your mark on the board    |
| G          | Switch game mode (PvP / AI)     |
| R          | Restart the game                 |
| 0          | AI plays randomly (easy mode)   |
| 1          | AI uses Minimax (unbeatable)    |
| Close      | Exit the game                   |

---

## Contribution

Want to add features like sound effects, animations, or different board sizes? Fork the repo, create your feature branch, and submit a PR. I’m open to ideas that make the game cooler!

---

## Contact

Created by **Harshil Madaan**  
Email: your.email@example.com  
GitHub: [Harshil-Madaan](https://github.com/Harshil-Madaan)

---

## Ready to dominate the Tic Tac Toe battlefield? Download, run, and challenge the unbeatable AI. Spoiler: it won’t go easy on you. 🎮🔥

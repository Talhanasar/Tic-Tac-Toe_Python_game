# 🕹️ Tic-Tac-Toe Game with Python & Pygame

Welcome to **Tic-Tac-Toe** — a classic game reimagined with Pygame! This game allows you to challenge another player or face off against an AI opponent powered by the **Minimax** algorithm. Enjoy an interactive and visually engaging experience as you make strategic moves, aiming to align three symbols in a row.

---

## 🎯 Objective

The Tic-Tac-Toe game is designed to offer players an intuitive and challenging experience:

- **Choose Your Side:** Play as either "X" or "O"
- **Single or AI Opponent:** Compete against another player or take on an AI opponent using the **Minimax algorithm**
- **Smooth Gameplay Flow:** From player selection to moves and results, everything is designed for an uninterrupted experience
- **Improved Skills:** Enhance your logical thinking and decision-making skills while playing!

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.x**
- **Pygame** library

Install Pygame by running:
```bash
pip install pygame
```

### Running the Game
Run the following command to start the game:

```bash
python runner.py
```
## 🎮 Gameplay
### Initial Screen
When you launch the game, a black screen appears with the title "Play Tic-Tac-Toe". Below, you'll see two options:

- **Play as O**
- **Play as X**
Simply click your preferred choice to start as either "X" or "O." After a brief pause for better user experience, you’ll be taken to the game board.

### Game Board Setup
Once you’ve selected a side, the game displays the Tic-Tac-Toe board:

- **3x3 Grid: Each square is outlined in white.**
- **Move Placement: Symbols ("X" or "O") appear in the center of the selected square.**

The board is ready for you to play your moves!

## 🧠 Game Logic and Flow

1. **Turn Handling:**
   - The game alternates turns between the player and the AI using the `player` function, which determines the current player.
  
2. **Checking Game Status:**
   - The `terminal` function monitors the board state to see if someone has won or if the game has ended in a tie.

### User Interaction and Moves
- **User's Move** : Click on any empty square on the grid to make a move. The game updates the board instantly based on your choice.
- **AI's Move** : If it's the AI's turn, the Minimax algorithm decides the optimal move. A brief pause (0.5 seconds) enhances the experience by simulating "thinking time" for the AI.

## 🏆 Game Over
When the game reaches a conclusion — either a win or a tie — a message appears to indicate the result. Additionally, a "Play Again" button pops up, allowing you to reset and start a new game!

If you click Play Again:

The game resets player choice, board state, and AI turn.
You’re back to the initial screen to begin anew!

## 📸 Screenshots

Initial Screen	Game Board	Game Over Screen
Replace path/to/initial.png, path/to/board.png, and path/to/gameover.png with the actual paths to your screenshot images.

## 💡 Technology & Algorithms

- **Python and Pygame** power the game's visuals and interaction.
- **Minimax Algorithm** for an unbeatable AI opponent — making optimal decisions each turn.

## 📈 Skills Enhanced

Playing this game helps improve:

- **Logical Thinking:** Plan and anticipate moves.
- **Decision-Making:** Strategize effectively to outwit the opponent.

Enjoy the game! 🕹️

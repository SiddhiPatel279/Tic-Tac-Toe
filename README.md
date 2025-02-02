# Tic-Tac-Toe Web Game

A simple Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. This project provides a user-friendly interface for playing the classic Tic-Tac-Toe game in a web browser.

## 🚀 Features

- Interactive 3x3 Tic-Tac-Toe game board
- Alternating turns between Player X and Player O
- Automatic win detection and game-over messages
- Tie detection if the board is full
- Reset game functionality
- Responsive UI with a modern design

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## 📂 File Structure

```
📦 Tic-Tac-Toe
├── 📄 index.html   # Main HTML structure
├── 📄 style.css    # Stylesheet for UI design
├── 📄 index.js     # JavaScript for game logic
└── 📂 assets       # Background images and other assets
```

## 📥 Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/tic-tac-toe.git
   ```
2. Navigate to the project directory:
   ```sh
   cd tic-tac-toe
   ```
3. Open `index.html` in a web browser.

## 🎮 How to Play

1. The game starts with Player X's turn.
2. Click on any empty box to place your symbol (X or O).
3. Players take turns until one player wins or the game ends in a tie.
4. The winner is declared if they align three symbols in a row, column, or diagonal.
5. Click the "New Game" button to reset and play again.

## 🔍 Code Highlights

- **Game Initialization**: The `initGame()` function resets the board and starts a new round.
- **Turn Handling**: `swapTurn()` manages player turns.
- **Win Detection**: `checkGameOver()` checks all possible winning positions.
- **Dynamic UI Updates**: JavaScript updates the DOM to reflect game progress.

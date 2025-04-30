# 🎮 Terminal Tic-Tac-Toe Game (Player vs Player / Player vs Computer)

A fun and interactive command-line Tic-Tac-Toe game built with Python, featuring:
- Player vs Player and Player vs Computer modes
- Colored display using ANSI escape codes
- Smart blocking strategy by the computer (no AI libraries)
- Lightly styled board with subtle numeric hints
- Replay support and clean win/draw detection

---

## 📂 Project Structure

```
tic_tac_toe/
│
├── main.py         # Entry point: handles game flow and user interaction
├── display.py      # Board display logic with ANSI styling
├── logic.py        # Game logic (win, draw, valid moves, AI strategy, etc.)
└── README.md       # Project documentation
```

---

## ✅ Features

- 🧑‍🤝‍🧑 **Two-Player Mode**  
  Take turns playing against a friend. X always plays first.

- 🤖 **Player vs Computer Mode**  
  The computer plays smartly — it can block winning moves and try to win.

- 🎨 **Color-coded Terminal Display**  
  - X in **red**
  - O in **green**
  - Unclaimed cells shown in **light grey** with position numbers

- 🔁 **Replay Support**  
  Choose to play again after a game ends — against human or computer.

- ⌛ **Realistic Computer Response Delay**  
  Simulated thinking time using `time.sleep()`.

---

## 🛠️ How to Run

1. Make sure you have **Python 3** installed.
2. Clone or download this repo.
3. Open a terminal and run:

```bash
python main.py
```

---

## 🧠 How It Works

- The board is a 3×3 grid represented as a list.
- Users enter a position (1–9) or a row/column combo (optional).
- The game checks for a win or draw after each move.
- ANSI escape codes format the display with colors and layout.
- The computer uses simple logic to:
  - Win if possible
  - Block the player's winning move
  - Otherwise pick the next best move

---

## 📸 Sample Board Display

```
 1 | 2 | 3
---+---+---
 4 | X | 6
---+---+---
 O | 8 | X
```

---

## 📦 Requirements

- No external libraries needed. Everything runs on standard Python 3.

---

## 💡 Future Improvements

- Add score tracking across rounds
- GUI version using Tkinter or PyGame
- Implement unbeatable AI using Minimax (optional challenge)

---

## 📄 License

MIT License — free to use and modify!



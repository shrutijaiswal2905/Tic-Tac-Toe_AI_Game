# 🎮 Tic-Tac-Toe AI Game (with GUI using Tkinter)

This is an interactive Tic-Tac-Toe game built with **Python** and **Tkinter**, featuring both **Single Player** (AI vs Human) and **Multiplayer** (Human vs Human) modes. The game utilizes the **Minimax algorithm** for optimal AI decision-making, and offers a sleek GUI that makes playing intuitive and fun.

---

## 🧠 About the Game

- 👤 **Single Player Mode**: Play against an intelligent AI using the **Minimax algorithm**.
- 👥 **Multiplayer Mode**: Play against a friend locally.
- 🎨 **Graphical UI**: Built using Tkinter for a smooth visual experience.
- 🔁 Restart the game at any time with a single click.

---

## ✨ Features

- 🎯 Accurate game logic with win and draw detection
- 💡 AI (O) plays optimally using the Minimax strategy
- 🖱️ Mouse-click event handling for interactive gameplay
- 🔄 Easy toggle between Single Player and Multiplayer modes
- 📲 Reset button to quickly restart a fresh game

---

## 🛠️ Tech Stack

- **Language**: Python 3.x  
- **GUI Library**: Tkinter  
- **AI Algorithm**: Minimax  
- **Widgets**:
  - `Frame`, `Button`, `Label` for layout and interactions

---

## 📁 Project Structure

```
tic_tac_toe_ai/
│
├── tic_tac_toe.py          # Main game script
└── README.md               # Project documentation
```

---

## 🚀 How to Run

### 🐍 Prerequisites

Make sure you have Python installed.

> **To install Tkinter** (usually pre-installed with Python):
```bash
pip install tk
```

### ▶️ Run the Game

```bash
python tic_tac_toe.py
```

- Select the mode: **SinglePlayer** or **Multiplayer**
- Click on the grid to make your move
- Watch the AI respond (in single-player mode)
- Hit **"Restart Game"** to play again

---

## 🔍 How AI Works (Minimax Algorithm)

In **Single Player Mode**, the computer ('O') uses **Minimax**, a recursive algorithm used in decision-making and game theory. It evaluates all possible future moves to choose the best one by assuming the opponent (player 'X') also plays optimally.

- 📈 Maximizes its own score (AI wants to win)
- 📉 Minimizes the opponent’s score (prevents human from winning)
- 🔄 Runs recursively to evaluate future moves
---

## 🔧 Possible Improvements

- Add difficulty levels (easy/medium/hard)
- Add sound effects and animations
- Enhance UI aesthetics with themes
- Allow saving score history
- Implement online multiplayer

---

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Built using the classic **Minimax Algorithm**
- Inspired by early AI game implementations
- Thanks to Python & Tkinter for making GUI dev fun and accessible!

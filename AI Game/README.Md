#readme
# 🎮 Connect Four with AI — Python + Pygame

A strategic twist on the classic Connect Four game with a powerful AI opponent! Built using Python, Pygame, and NumPy.

---

## 🧰 Requirements

Install the required libraries using pip:

*pip install pygame numpy*

Included Standard Libraries:
- math — mathematical functions
- random — for AI move selection
- sys — system-level operations

## 🚀 Features
- 🎯 Real-time UI with intuitive gameplay
- 🧠 AI opponent using Minimax algorithm + Alpha-Beta Pruning
- 🔁 Restart and Quit functionality
- ⚡ Efficient board computation using NumPy
- 🧩 Heuristic evaluation for adaptive AI strategy

## 🕹 How to Run
- Clone the repository or download the .py file
- Open terminal or command prompt
- Navigate to the project directory
- Run the game:
python connect_four_ai.py



## 🎮 How to Play
📋 Main Menu
- Press 1 → Play first as Red
- Press 2 → Let AI play first as Yellow
- Press Q → Quit the game
🧩 In Game
- Hover over a column → highlights potential drop
- Click a column → drops your chip
- First to Connect Four wins!
Win Types:
- Horizontal
- Vertical
- Diagonal
🔚 Game Over Screen
- Displays Winner: Player or AI
- Press Y → Restart the game
- Press N → Exit

## 🧠 AI Strategy
The AI uses the Minimax algorithm with Alpha-Beta Pruning, making it quick and tactical.
Heuristic Evaluation:
- Rewards 2, 3, and 4 connected pieces
- Prioritizes control of the center column
- Employs defensive logic to block player threats

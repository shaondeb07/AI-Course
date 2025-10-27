
# 🎮 ##GAme 1, Connect Four with AI — Python + Pygame

A strategic twist on the classic ##Connect Four color game## with a powerful AI opponent! Built using Python, Pygame, and NumPy.

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

--------------



# ♟️ ##GAme 2## Chess Game with AI — Python + Pygame

A modern and strategic version of **Chess** featuring an intelligent AI opponent!  
Built using **Python**, **Pygame**, and **python-chess**, this game blends logic and design for an engaging play experience.

---

## 🧰 Requirements

Install the required libraries using pip:

```
pip install pygame chess
```

Included Standard Libraries:
- **math** — mathematical operations  
- **sys** — system-level functions  

---

## 🚀 Features
- 🎮 Fully interactive chessboard with real-time move validation  
- 🧠 AI opponent powered by the **Minimax Algorithm** + **Alpha-Beta Pruning**  
- ⚡ Smart board evaluation based on piece values and positions  
- 💡 Highlights legal moves and selected pieces  
- 🔁 Restart and Quit options after each match  
- 🏁 Displays winner or draw condition at the end of the game  

---

## 🕹 How to Run
1. Clone the repository or download the `.py` file  
2. Open your terminal or command prompt  
3. Navigate to the project directory  
4. Run the game:
   ```
   python chess.py
   ```

---

## 🎯 How to Play
### 📋 Gameplay
- You play as **White** (first move)  
- Click a piece to select it → valid moves will be highlighted  
- Click a highlighted square to move the piece  
- The AI (Black) automatically makes its move after yours  

### 🏆 Game End
- The screen displays the winner:  
  - **Player Wins!** (if you checkmate the AI)  
  - **Computer Wins!** (if AI checkmates you)  
  - **Draw** (if stalemate or repetition occurs)
- After result display → game automatically closes  

---

## 🧠 AI Strategy
The AI uses the **Minimax Algorithm with Alpha-Beta Pruning**, evaluating multiple future board states to choose the optimal move.

### ♜ Evaluation Logic
- Material balance (piece value differences)  
- Checkmate, stalemate, or draw detection  
- Defensive and offensive play through depth search  
- Promotion handling for pawns  

You can adjust the AI difficulty by editing this line inside the code:
```python
_, move = minimax(board, 2, -math.inf, math.inf, False)
```
Increase the number `2` for deeper (smarter but slower) AI calculations.

---

## 🧩 Technologies Used
- **Python 3.x**
- **Pygame**
- **python-chess**
- **Minimax Algorithm**
- **Alpha-Beta Pruning**

---



# 🎮 ##GAme 3 Tic-Tac-Toe (AI Version) — Python + Tkinter + Minimax

A simple yet powerful **Tic-Tac-Toe game** built with **Python and Tkinter**, featuring an **unbeatable AI opponent** using the **Minimax Algorithm**.  
Play against the computer in a smooth and interactive GUI experience!

---

## 🧰 Requirements

Install dependencies before running the game:

```
pip install tk
```

*(Tkinter usually comes pre-installed with Python, so you might already have it!)*

---

## 🚀 Features
- 🎨 Interactive GUI built with **Tkinter**
- 🧠 **AI opponent** powered by **Minimax algorithm**
- 🔁 Automatic game restart after win/draw
- ⚡ Instant move response (with a small delay for realism)
- 🏆 Detects win, loss, or draw accurately

---

## 🕹️ How to Play
1. Run the game using:
   ```
   python tic_tac_toe_ai.py
   ```
2. You play as **X**, the computer plays as **O**
3. Click any empty square to make your move
4. The AI will respond automatically
5. Game ends when:
   - You win 🎉  
   - The AI wins 🤖  
   - It’s a draw 😐  

---

## 🧠 How the AI Works
The computer uses the **Minimax Algorithm**, which explores all possible game outcomes to find the **optimal move**.

### 🔍 Algorithm Logic:
- +1 → AI win  
- -1 → Player win  
-  0 → Draw  

AI tries to **maximize** its score while minimizing yours — meaning it *never loses*. 😈

---

## 🧩 Key Components
- **Tkinter** → GUI buttons and grid  
- **Minimax** → Decision-making algorithm  
- **Math** → Used for scoring and comparison  
- **Messagebox** → Shows result popups  

---

## 🧠 Code Overview
| Function | Description |
|-----------|--------------|
| `on_click(index)` | Handles user moves |
| `computer_move()` | Calculates and plays AI move |
| `minimax(depth, is_maximizing)` | Core AI logic |
| `check_winner(player)` | Checks for win condition |
| `reset_board()` | Resets game after round ends |

---

## 🧑‍💻 Author
**Saykat Dev Shaon**  
*Department of Computer Science & Engineering (CSE)*  
Project for the **AI Course**

---



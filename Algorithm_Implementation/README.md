

# 🤖 Artificial Intelligence Search & Game Algorithms  

This repository contains implementations and explanations of classic **AI Search Algorithms** and **Game Algorithms**.  
Each section describes **how the algorithm works**, **where it is used**, **its complexity**, and includes **sample input-output images**.

---

## 🔍 1. A* Search Algorithm  

### 🧠 How It Works  
A* is an **informed search algorithm** that finds the shortest path using a combination of **actual cost (g(n))** and **heuristic cost (h(n))**.  
The total cost function is:  
> **f(n) = g(n) + h(n)**  

It expands the path that appears most promising based on this evaluation.

### 💡 Applications  
- Pathfinding in maps (e.g., Google Maps)  
- Robotics and game movement  
- Puzzle solving (8-puzzle, 15-puzzle)

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(E) or O(b^d) |
| Space | O(b^d) |

### 🖼️ Input / Output  
![A* Example](https://via.placeholder.com/800x300?text=A*+Pathfinding+Example)

---

## 🧮 2. Alpha-Beta Pruning  

### 🧠 How It Works  
An optimization of the **Minimax Algorithm** used in game trees.  
It prunes branches that cannot affect the final decision, reducing computation.  

### 💡 Applications  
- Chess, Tic-Tac-Toe, Checkers  
- Decision making in turn-based games  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(b^(d/2)) |
| Space | O(b*d) |

### 🖼️ Input / Output  
![Alpha-Beta Example](https://via.placeholder.com/800x300?text=Alpha-Beta+Tree+Pruning+Example)

---

## 🔁 3. Breadth-First Search (BFS)  

### 🧠 How It Works  
BFS explores all nodes at the current depth before moving to the next level.  
It uses a **queue** data structure.

### 💡 Applications  
- Shortest path in unweighted graphs  
- Social network analysis  
- Web crawling  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(V + E) |
| Space | O(V) |

### 🖼️ Input / Output  
![BFS Example](https://via.placeholder.com/800x300?text=BFS+Traversal+Example)

---

## ⚡ 4. Beam Search  

### 🧠 How It Works  
A **heuristic search** that explores a graph by expanding the best *k* nodes at each level, reducing memory usage compared to A*.  

### 💡 Applications  
- Natural Language Processing  
- Machine Translation  
- Speech Recognition  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(b*k) |
| Space | O(b*k) |

### 🖼️ Input / Output  
![Beam Search Example](https://via.placeholder.com/800x300?text=Beam+Search+Path+Example)

---

## 🌟 5. Best First Search  

### 🧠 How It Works  
Uses a **priority queue** to explore the most promising node based on heuristic value h(n).  

### 💡 Applications  
- GPS Navigation  
- Network Routing  
- AI Game agents  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(b^m) |
| Space | O(b^m) |

### 🖼️ Input / Output  
![Best First Example](https://via.placeholder.com/800x300?text=Best+First+Search+Example)

---

## 🔄 6. Bidirectional Search  

### 🧠 How It Works  
Runs two simultaneous searches — one forward from the start node, and one backward from the goal node — and meets in the middle.  

### 💡 Applications  
- Shortest path problems  
- GPS systems  
- Social connection degree search  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(b^(d/2)) |
| Space | O(b^(d/2)) |

### 🖼️ Input / Output  
![Bidirectional Example](https://via.placeholder.com/800x300?text=Bidirectional+Search+Example)

---

## 🌀 7. Depth-First Search (DFS)  

### 🧠 How It Works  
DFS explores as far as possible along each branch before backtracking.  
It uses a **stack** or **recursion**.  

### 💡 Applications  
- Maze solving  
- Topological sorting  
- Pathfinding in games  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(V + E) |
| Space | O(V) |

### 🖼️ Input / Output  
![DFS Example](https://via.placeholder.com/800x300?text=DFS+Traversal+Example)

---

## ⬇️ 8. Depth-Limited Search (DLS)  

### 🧠 How It Works  
A variation of DFS with a fixed depth limit to prevent infinite loops.  

### 💡 Applications  
- Game trees with limited depth  
- Exploring large search spaces safely  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(b^l) |
| Space | O(b*l) |

### 🖼️ Input / Output  
![DLS Example](https://via.placeholder.com/800x300?text=Depth+Limited+Search+Example)

---

## 🔁 9. Iterative Deepening Search (IDS)  

### 🧠 How It Works  
Combines DFS’s space efficiency and BFS’s completeness.  
It performs DLS repeatedly with increasing depth limits.  

### 💡 Applications  
- Pathfinding in large graphs  
- AI game playing (chess, puzzles)  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(b^d) |
| Space | O(b*d) |

### 🖼️ Input / Output  
![IDS Example](https://via.placeholder.com/800x300?text=Iterative+Deepening+Example)

---

## 🎮 10. Minimax Algorithm  

### 🧠 How It Works  
Used for **two-player games**.  
Each level alternates between **maximizing** (player) and **minimizing** (opponent) nodes to choose the optimal move.  

### 💡 Applications  
- Chess, Tic-Tac-Toe, Checkers  
- Decision-making systems  

### 🧮 Complexity  
| Type | Complexity |
|------|-------------|
| Time | O(b^m) |
| Space | O(b*m) |

### 🖼️ Input / Output  
![Minimax Example](https://via.placeholder.com/800x300?text=Minimax+Game+Tree+Example)

---

## 🧾 Summary Table  

| Algorithm | Type | Applications | Time Complexity | Space Complexity |
|------------|------|---------------|-----------------|------------------|
| A* | Informed | Pathfinding | O(E) | O(b^d) |
| Alpha-Beta | Game | Chess, Tic Tac Toe | O(b^(d/2)) | O(b*d) |
| BFS | Uninformed | Shortest Path | O(V+E) | O(V) |
| Beam Search | Informed | NLP, Speech | O(b*k) | O(b*k) |
| Best First | Informed | Navigation | O(b^m) | O(b^m) |
| Bidirectional | Uninformed | GPS | O(b^(d/2)) | O(b^(d/2)) |
| DFS | Uninformed | Graph Traversal | O(V+E) | O(V) |
| DLS | Uninformed | Depth-Limited Tree | O(b^l) | O(b*l) |
| IDS | Uninformed | Pathfinding | O(b^d) | O(b*d) |
| Minimax | Game | Chess, Checkers | O(b^m) | O(b*m) |

---

## 🧑‍💻 Author  
**Name:** Saykat Dev Shaon  
**Department:** Computer Science & Engineering  
**Institution:** North East University Bangladesh  
**Project Type:** AI Algorithms Analysis  

# Chess Engine in Python

This is a custom-built chess engine implemented in Python using the `python-chess` library. It supports basic features such as random move generation, material and positional evaluation, Minimax algorithm, Alpha-Beta pruning, and iterative deepening search.

---

##  Features

-  FEN-based game initialization
-  Random move generation
-  Material evaluation
-  Positional evaluation using piece-square tables
-  Minimax search
-  Alpha-Beta pruning
-  Iterative Deepening Search
-  Move ordering optimization
-  Performance testing with node count and execution time

---

## Tech Stack

- Python 3.10+
- [python-chess](https://python-chess.readthedocs.io/en/latest/) — Chess board representation and move legality

---

##  Project Structure

chess-engine/
│
├── engine.py # Main chess engine implementation
├── README.md # Project documentation
└── requirements.txt # Dependencies



---

## ▶️ Getting Started

### 1. Clone the repository

git clone https://github.com/PRANAV-J-G/Chess-Engine.git
cd Chess-Engine

### 2. Install requirements
pip install -r requirements.txt

### 3. Run the flask application 

python flask_app.py

🧠 Algorithms
Minimax: Recursive brute-force game tree exploration.

Alpha-Beta Pruning: Cuts off unnecessary branches to improve efficiency.

Iterative Deepening: Performs repeated deepening of search to improve move ordering and pruning.


## Screenshot 

![alt text](assets/Screenshot_20250609_120241.png)
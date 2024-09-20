# Tic-Tac-Toe

This is a simple implementation of the classic **Tic-Tac-Toe** game, where the AI opponent is powered by the **Minimax algorithm** to play optimally and never lose.

## Features
- **Single Player Mode**: Play against the AI.
- **AI Powered by Minimax Algorithm**: The AI opponent will always make the best possible move, ensuring a challenging gameplay experience.
- **2D Grid Interface**: User-friendly visual representation of the game board.
- **Win, Lose, or Draw**: Proper game-ending scenarios for a fair match.

## How the Minimax Algorithm Works
The Minimax algorithm is a recursive function that evaluates all possible moves from a given game state and chooses the move that maximizes the player's chances of winning while minimizing the opponent's chances. The AI always assumes the opponent will play optimally, and thus it seeks the best possible move at each step.

- **Maximizer**: Tries to win the game (AI).
- **Minimizer**: The human opponent trying to beat the AI.

The AI uses this algorithm to calculate the best move by simulating every possible outcome of each available move.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Rudraksh22Menon/Tic-Tac-Toe.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Tic-Tac-Toe
   ```
3. Run the game (assuming it is a Python project):
   ```bash
   python tictactoe.py
   ```

## How to Play
1. The game starts with an empty 3x3 grid.
2. The player selects an empty cell to place their mark (X).
3. The AI (O) responds with the best move based on the Minimax algorithm.
4. The game continues until either player wins or all cells are filled, resulting in a draw.

## Technologies Used
- **Programming Language**: Python
- **Algorithm**: Minimax

## Future Enhancements
- Add a **2-player mode** to allow two humans to play.
- Implement **difficulty levels** (Easy, Medium, Hard) by adjusting the depth of the Minimax search tree.
- Add a **graphical user interface (GUI)** for a better user experience.

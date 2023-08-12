# Tic Tac Toe Game

Welcome to the Tic Tac Toe game implemented in Python. This simple text-based game allows two players to take turns and compete to form a line of their respective symbols ('X' or 'O') on the game board.

## How to Play

1. Clone this repository to your local machine or download the code files.
2. Open your terminal or command prompt and navigate to the directory containing the game files.
3. Run the `tic_tac_toe.py` script using the following command:

```bash
python tic_tac_toe.py
```

4. Follow the on-screen instructions to take turns and make your moves.

## Game Rules

- The game is played on a 3x3 grid.
- Players take turns choosing an available number (1-9) on the grid.
- The first player uses 'X' as their symbol, and the second player uses 'O'.
- To win, a player must have three of their symbols in a horizontal, vertical, or diagonal line.
- The game ends when a player wins, there is a tie, or all the grid spaces are filled.

## Example Gameplay

```
Welcome to Tic Tac Toe
----------------------

+---+---+---+
| 1 | 2 | 3 |
+---+---+---+
| 4 | 5 | 6 |
+---+---+---+
| 7 | 8 | 9 |
+---+---+---+

Player 1's turn (X)
Choose a number [1-9]: 5

+---+---+---+
| 1 | 2 | 3 |
+---+---+---+
| 4 | X | 6 |
+---+---+---+
| 7 | 8 | 9 |
+---+---+---+

Player 2's turn (O)
Choose a number [1-9]: 1

+---+---+---+
| O | 2 | 3 |
+---+---+---+
| 4 | X | 6 |
+---+---+---+
| 7 | 8 | 9 |
+---+---+---+

...

Player 1's turn (X)
Choose a number [1-9]: 9

+---+---+---+
| O | X | X |
+---+---+---+
| 4 | X | O |
+---+---+---+
| O | O | X |
+---+---+---+

Congratulations! Player 1 (X) wins!
```

Enjoy the game and have fun playing!

## Disclaimer

This code was provided for educational purposes and may contain bugs or areas for improvement. Feel free to enhance the game's functionality and design as you see fit.

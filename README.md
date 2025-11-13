# tic-tac-toe-game-in-python
Simple command-line Tic-Tac-Toe in Python — user vs computer, win/draw detection, and random computer moves. Great beginner project demonstrating functions, lists, control flow, and basic game logic.
A simple command-line Tic-Tac-Toe game written in Python.  
Player is 'O' (user) and the computer plays 'X'. The game supports:
- User input for moves (1–9)
- Random computer moves (avoids occupied cells)
- Win detection for rows, columns and diagonals
- Draw detection (no free cells left)
- $ python tic_tac_toe.py
[1, 2, 3]
[4, X, 6]
[7, 8, 9]


Example gameplay:
Board squares are numbered 1–9 (row-major).
You enter the number of the square where you want to place 'O'.
Computer places 'X' at a random free cell.
After each move the board is printed and the game checks for win/draw.

Future improvements (ideas):
major improvements on. If the user enters a position that’s already taken → tell them “occupied, choose again!” also for If the computer randomly picks a filled cell → force it to pick again until it finds a free one.
Improve computer player using Minimax (perfect play).
Add replay option and better input validation.
Add a nicer CLI board with separators or a GUI (Tkinter / Pygame).
Add unit tests for utility functions (win detection, free field list).

# Tic-Tac-Toe Game

A simple desktop Tic-Tac-Toe game built with Python and Tkinter. Two players can take turns on the same device, with the interface showing the current player and highlighting the winning line in green.

## Features

- 3x3 clickable game board
- Two-player turn-based gameplay
- Current player indicator
- Winning line highlighted in green
- Automatic reset after a win

## Requirements

- Python 3.x
- Tkinter (usually included with standard Python installations)

## How To Run

From the project folder, run:

```bash
python tictactoagame.py
```

If your system uses a specific Python launcher, you can also try:

```bash
py tictactoagame.py
```

## How To Play

1. Player X starts the game.
2. Click any empty square to place your mark.
3. Players alternate turns after each valid move.
4. The first player to complete a row, column, or diagonal wins.
5. After a win, the board resets automatically.

## Project Structure

- `tictactoagame.py` - main game script

## Notes

- The game is designed for local two-player use.
- The current version resets the board automatically when a player wins.

## Future Improvements

- Add a draw detection message
- Add score tracking
- Add a restart button
- Improve the UI styling

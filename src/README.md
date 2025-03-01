# Chess Game

A simple chess game built using **Python** and **Pygame**. This game allows users to play chess with move validation, piece dragging, and theme switching.

## Features

- **Drag and Drop Mechanics**: Move pieces smoothly across the board.
- **Valid Move Indication**: Highlights available moves for the selected piece.
- **Move History Tracking**: Displays the last move played.
- **Theme Switching**: Change the board's appearance dynamically.
- **Sound Effects**: Play sounds for moves and captures.
- **Reset Game**: Restart the game anytime.

## Installation

### Prerequisites
Ensure you have Python installed (Python 3.8+ recommended). You also need to install `pygame`.

```bash
pip install pygame
```

### Clone the Repository

```bash
git clone https://github.com/SaatvikSS/Chess_Game.git
cd Chess_Game
```

## How to Play

1. Run the game:
   ```bash
   python main.py
   ```
2. Click on a piece to see available moves.
3. Drag and drop the piece to a valid square.
4. Press `T` to change the theme.
5. Press `R` to reset the game.
6. Close the window or press `Ctrl+C` in the terminal to exit.

## Project Structure

```
Chess_Game/
│-- const.py         # Constants for board size, colors, etc.
│-- main.py          # Main game loop
│-- game.py          # Game logic
│-- board.py         # Board setup and piece movement logic
│-- dragger.py       # Handles piece dragging
│-- move.py          # Move validation and rules
│-- square.py        # Square properties and positioning
│-- config.py        # Configuration for themes and sounds
```

## Future Enhancements
- Implement AI for single-player mode.
- Add a timer for competitive play.
- Introduce online multiplayer.

---
Developed by **Saatvik Shashank Shrivastava** 🎮♟️

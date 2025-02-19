## 2048 Game Implementation

This repository contains an implemented version of the classic 2048 game, built with JavaScript. The game logic is structured within a Game class, while the user interface is handled separately using HTML, CSS, and JavaScript.    
[DEMO LINK](https://darianastas.github.io/js_2048_game_DN/)
### Features

- Fully functional 2048 gameplay with number merging and movement logic.
- Custom styling applied for a unique look and feel.
- Smooth user interaction using keyboard arrow keys.
- Dynamic UI updates reflecting game state changes in real-time.
- Winning and losing conditions are properly handled.
- Random tile generation after each valid move.
- Score tracking that increases based on merged tile values.

*Start and restart functionality to reset the game at any time.*

### Game Rules

The game field consists of a 4x4 grid. Players can move tiles using the arrow keys. Tiles slide in the chosen direction until they hit the edge or another tile. Two tiles with the same number merge into one with double the value. A merged tile cannot be merged again during the same move. After each move, a new tile (2 or 4) appears in a random empty cell. The game is won when a tile reaches 2048. The game is over when no more moves are available. 

### Implementation Details

**Game.class.js** contains the core logic of the 2048 game, including tile movement, value merging, new number generation, and determining the game state (win, loss, or continuation).   
**main.js** handles the integration of game logic with the UI, processes keyboard events, updates the DOM, and displays messages about the game state.

### How to Play

1. Clone the repository   
git clone https://github.com/DariaNastas/js_2048_game_DN   
cd rjs_2048_game_DN    
1. Install dependencies   
npm install   
1. Start the local server   
npm start   
1. When the project runs in the browser, press the "Start" button and use the arrow keys to move the tiles.   

*Merge tiles to reach 2048 and win the game!*


## Enjoy playing 2048! 🎮

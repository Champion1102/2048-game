# 2048 Game - Online

Welcome to the classic 2048 game, playable online! The objective of the game is to combine tiles of the same number to reach the **2048** tile. You can try it out here: [2048 Game](https://2048-game-olive.vercel.app).

## Table of Contents

- [Game Rules](#game-rules)
- [Features](#features)
- [Technologies](#technologies)
- [How to Play](#how-to-play)
- [Development](#development)
- [License](#license)

## Game Rules

- **Objective**: Combine the numbered tiles on the grid to create the 2048 tile.
- **Gameplay**:
  - Use arrow keys to slide tiles on a 4x4 grid.
  - Tiles with the same number merge into one when they collide.
  - Each move adds a new tile (either 2 or 4) to an empty spot on the board.
  - The game is won when a tile reaches 2048.
  - The game ends if no moves are possible.

## Features

- Simple, classic design inspired by the original 2048.
- Score tracking: watch your score increase as tiles merge.
- Restart option to play again anytime.
- Win and lose conditions displayed on the screen.

## Technologies

- **HTML5** for the structure.
- **CSS3** for styling and layout.
- **JavaScript** for game logic, controls, and DOM manipulation.

## How to Play

1. Open the game in your browser by visiting [2048 Game](https://2048-game-olive.vercel.app).
2. Use your keyboard arrow keys to move the tiles in the four directions (left, right, up, down).
3. Tiles with the same value merge to form a new tile that is the sum of the two.
4. Keep playing until you reach the 2048 tile. You win!
5. If no more moves are possible, the game will display a "Game Over" message.

## Development

This game is built using plain JavaScript for handling the grid, tile movement, and merging logic. CSS is used to style the grid and the tiles, while HTML provides the structure of the page.

### To Run Locally

1. Clone this repository.
2. Open the `index.html` file in a web browser.

### Future Enhancements

- Add animations for tile movements and merges.
- Introduce a score leaderboard for players.

## License

This project is open-source and available under the [MIT License](LICENSE).

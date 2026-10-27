# Tic-Tac-Toe

A local two-player browser game built with HTML, CSS, and vanilla JavaScript.

[Play the game](https://rkodirkhonov.github.io/tictactoe/)

## How it works

X starts. Two players take turns selecting an empty square on a 3 × 3 board. Three matching marks in a row, column, or diagonal win the round. A full board without a winner is a draw. Use Restart to play again.

## Run locally

Clone the repository and open `index.html` in a browser. No package installation or build step is required.

```bash
git clone https://github.com/rkodirkhonov/tictactoe.git
cd tictactoe
```

## Code map

| File | Responsibility |
| --- | --- |
| `index.html` | Board and game controls |
| `styles.css` | Layout, marks, hover states, and result overlay |
| `script.js` | Turns, eight winning combinations, draw detection, and restart behavior |

## Screenshots

![Game board](https://user-images.githubusercontent.com/37968028/212334075-85e4d759-59f9-4322-99ef-b1d2bf191349.png)

![X wins](https://user-images.githubusercontent.com/37968028/212334326-c8735c6a-36ea-46c4-b808-3004bcdb64c4.png)

Screenshots and the demo link are retained from the original README.

## Learning focus

DOM event handling, state transitions, array operations, and separating game rules into functions.

## Next improvements

- [ ] Keyboard-operable cells and an announced turn/result status.
- [ ] Tests for all winning combinations, draws, and restart behavior.
- [ ] A score counter across rounds.
- [ ] Optional computer opponent after the core rules are covered by tests.

This is a fundamentals project: local play only, with no backend or online multiplayer.

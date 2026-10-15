# Rock Paper Scissors Game

A simple interactive Rock Paper Scissors game built with HTML, CSS, and JavaScript.

The player competes against the computer, which randomly selects rock, paper, or scissors. The game keeps track of wins, losses, and ties, and saves the score using the browser's local storage.

## Features

- **Play against the computer:** Choose rock, paper, or scissors.
- **Score tracking:** Keep track of wins, losses, and ties.
- **Persistent score:** The score is saved in `localStorage`, so it remains available after refreshing the page.
- **Auto Play:** Let the computer play automatically until you stop it.
- **Keyboard controls:** Play using your keyboard.
- **Reset score:** Reset the score with a confirmation message before clearing it.

## Keyboard Controls

| Key | Action |
|---|---|
| `R` | Choose Rock |
| `P` | Choose Paper |
| `S` | Choose Scissors |
| `A` | Start or stop Auto Play |
| `Backspace` | Reset the score |

## Technologies Used

- **HTML5** — Structures the game and its buttons.
- **CSS3** — Styles the interface and game elements.
- **JavaScript** — Implements the game logic and interactive features.
- **DOM manipulation** — Updates the score, moves, and game results on the page.
- **Event listeners** — Respond to button clicks and keyboard input.
- **localStorage** — Saves the score between page refreshes.
- **JSON** — Converts the score object to and from a string for storage.

## Project Structure

```text
rock-paper-scissors/
├── img/
│   ├── paper-emoji.png
│   ├── rock-emoji.png
│   └── scissors-emoji.png
├── script/
│   └── rock-paper-scissors.js
├── style/
│   └── rock-paper-scissors.css
├── rock-paper-scissors.html
└── README.md
```

## How to Run the Game

1. Clone or download this repository.
2. Open `rock-paper-scissors.html` in your browser.
3. Click one of the three move buttons or use the keyboard controls.
4. Try Auto Play and the Reset Score feature.

## What I Learned

While building this project, I practised:

- Selecting and updating HTML elements with JavaScript.
- Using `addEventListener()` to handle user interactions.
- Working with objects to track the game score.
- Using `localStorage`, `JSON.stringify()`, and `JSON.parse()` to persist data.
- Using `Math.random()` to generate the computer's move.
- Using `setInterval()` and `clearInterval()` to implement Auto Play.
- Using conditional statements to determine the winner.

## Future Improvements

- Make the game more responsive on different screen sizes.
- Improve accessibility and keyboard controls.
- Add animations and visual feedback for each round.
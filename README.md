# Jungle Flip Game

## Description

Jungle Flip is a classic card memory game built with HTML, CSS, and JavaScript. The goal of the game is to find all the matching pairs of cards in the shortest time and with the fewest moves possible.

This project is a web-based game designed for entertainment and to test memory skills.

## Game Functionality

The game has three levels of difficulty:

- **Easy:** 6 pairs of cards (3x4 grid) and a time limit of 1 minute.
- **Medium:** 8 pairs of cards (4x4 grid) and a time limit of 1.5 minutes.
- **Hard:** 10 pairs of cards (4x5 grid) and a time limit of 2 minutes.

The player can choose a level and start playing. The game tracks the number of moves and the remaining time. The player wins the game by matching all the cards before the time runs out.

## Features

### HTML

-   **Structure:**
    -   The game board is created dynamically using JavaScript and is structured using a grid layout.
    -   Cards are represented by  `div`  elements with appropriate classes for styling and identification.
    -   A timer, a move counter, and a restart button are included for user interaction.
-   **Accessibility:**
    -   The game elements have semantic HTML tags to improve accessibility for screen readers and other assistive technologies.
    -   Alternative text is provided for images.

### CSS

-   **Styling:**
    -   The game has an attractive and responsive design, making it playable on various screen sizes.
    -   Cards are visually appealing and have a flip animation using CSS transitions for a smooth user experience.
-   **Responsiveness:**
    -   Media queries are used to ensure the game layout adapts to different screen sizes, providing an optimal experience on desktops, tablets, and mobile devices.

### JavaScript

-   **Game Logic:**
    -   The game logic is implemented in JavaScript, handling card shuffling, flipping, matching, and checking for win/lose conditions.
    -   The game board is generated dynamically based on the selected difficulty.
-   **Timer:**
    -   A timer is implemented to track the remaining time. The game ends when the timer reaches zero.
-   **Move Counter:**
    -   A move counter keeps track of the player's moves, providing feedback on their performance.
-   **Sound Effects:**
    -   Sound effects are incorporated to enhance the gaming experience, providing auditory feedback for actions like card flips, matches, and game over.
-   **Local Storage:**
    -   The game uses local storage to preserve the game state, even if the user accidentally closes or refreshes the browser window.

## How to Play

1.  Open `index.html` in your web browser.
2.  Select a level of difficulty by clicking on one of the level cards (Easy, Medium, or Hard).
3.  The game will start, and the timer will begin counting down.
4.  Click on the cards to flip them and reveal the animal pictures.
5.  Try to remember the location of the matching cards.
6.  When you find two matching cards, they will stay flipped over.
7.  Continue flipping cards and matching pairs until all cards are face up.
8.  If you match all the cards before the timer runs out, you win!
9.  If the timer runs out before you've matched all the cards, you lose. You can try again by clicking the "Restart" button.

## Files and Directory Structure

```
jungle-flip-game/
├──
│   ├── img1.jpeg
│   ├── i1.gif
│   ├── buttonlogo.png
│   ├── back2.jpeg
│   ├── cardPic.jpeg
│   ├── pic1.jpeg
│   ├── pic2.jpeg
│   ├── pic3.jpeg
│   ├── pic4.jpeg
│   ├── pic5.jpeg
│   ├── pic6.jpeg
│   ├── pic.7.jpeg
│   ├── pic8.jpeg
│   ├── pic9.jpeg
│   ├── pic10.jpeg
│   ├── jungleSound.mp3
│   ├── match.mp3
│   ├── noMatch.mp3
│   ├── touch.mp3
│   ├── win.mp3
│   ├── index.html
│   ├── secondPage.html
│   ├── secondPage.css
│   ├── easy.html
│   ├── easy.css
│   ├── easy.js
│   ├── mid.html
│   ├── mid.css
│   ├── mid.js
│   ├── hard.html
│   ├── hard.css
│   └── hard.js

```

## Future Improvements

-   Add more levels of difficulty.
-   Implement a scoring system based on the time taken and the number of moves.
-   Add different card themes.
-   Improve the game's accessibility for users with disabilities.

## Contributing

Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

# Tic Tac Toe Game

This repository contains a simple Tic Tac Toe game implemented using HTML, CSS, and JavaScript. Players can take turns to play the classic Tic Tac Toe game on a 3x3 grid.

## Features 

1.  Interactive Gameplay: The game allows two players to take turns by clicking on the grid cells to place their symbols ("X" or "O").
2.  Dynamic Game Board: The game board is dynamically generated using HTML and CSS, making it responsive and adaptable to various screen sizes.
3.  Real-Time Updates: The game updates in real-time to show whose turn it is, whether a player has won, or if the game ends in a draw.
4.  Winning Condition Detection: The game logic in game_logic.js checks for winning conditions after each move to determine if a player has won the game.
5.  Restart Functionality: Players can restart the game at any time by clicking the "Restart" button. This function resets the game board and sets the player text back to "Tic Tac Toe."
6.  Styling and Animation: The game has a visually appealing design with custom fonts and animations for the "Restart" button on hover.
7.  Responsive Design: The game interface is designed to be responsive, ensuring a good user experience across different devices.
8.  Error Handling: The game code includes error handling to prevent invalid moves and ensure smooth gameplay.
9.  Customizable Colors: The game uses CSS custom properties (--orange and --winner_blocks) to easily customize the color scheme.
10. Modular Code Structure: The JavaScript code is organized into functions, promoting readability and maintainability.
11. No External Libraries: The project uses only vanilla HTML, CSS, and JavaScript without relying on any external libraries or frameworks.
12. Graceful Draw Handling: When the game ends in a draw, the "Draw Game!" message is displayed, and the boxes change color to indicate the draw.
13. Accessibility: The game has accessible features, such as color contrast and text alternatives for screen readers.
14. Consistency: The game maintains a consistent UI design and user experience.
15. Scalability: The code structure allows for easy scaling and potential future enhancements, such as adding AI opponents or different board sizes.

## How to Play

1. Open the `index.html` file in your web browser.
2. The game starts with Player 1 (X) making the first move.
3. Players take turns to click on an empty cell in the grid to place their respective symbols (X or O).
4. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.
5. If all the cells are filled and no player has three symbols in a row, the game ends in a draw.

## Files

- `game_logic.js`: This JavaScript file contains the game logic, event handlers, and functions for checking the winner and draw conditions.
- `index.html`: The main HTML file containing the game board and user interface elements.
- `style.css`: The CSS file containing styles for the game board and user interface.

## Technologies Used

- HTML
- CSS
- JavaScript

## Live Demo

 Check out the live demo [here](https://tic-tac-toe-game-melvin.vercel.app/).

## How to Contribute

Contributions to this project are welcome! If you have any improvements or new features to add, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

The project was created by Melvin K J.

## Acknowledgments

Thanks to the creators of the [Finger Paint font](https://fonts.google.com/specimen/Finger+Paint) used in this project.

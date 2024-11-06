# Simon Game

The **Simon Game** is a memory game where the player must repeat the sequence of colors that is randomly generated. The game increases in difficulty with each level by adding a new color to the sequence. The player must remember the sequence and click the corresponding buttons in the correct order. If the player makes a mistake, the game ends and prompts the user to press a key to restart.

## Features
- **Random color sequence**: The game generates a random sequence of colors that the user must follow.
- **Increasing difficulty**: The game difficulty increases with each level, as a new color is added to the sequence.
- **Game over effect**: If the user makes a mistake, the game shows a "game over" flash effect and plays a "wrong" sound.
- **Keyboard interaction**: The game can be started by pressing any key.

## Demo

You can try out the game [here](https://jemogithirwa4.github.io/Simon-Game/).

## Technologies Used
- **HTML**: The structure of the game, including buttons and titles.
- **CSS**: Styling the game elements and adding visual effects.
- **JavaScript**: Game logic, event handling, and user interaction.
- **jQuery**: Used for DOM manipulation and animations.
- **Audio**: Sounds for the game (correct and wrong answers).

## Setup and Installation

To run this game locally, follow these steps:

1. Clone this repository to your local machine using the following command:
    ```bash
    git clone https://github.com/JemoGithirwa4/Simon-Game.git
    ```

2. Open the `index.html` file in your browser to play the game.

3. Ensure you have the necessary sound files (`red.mp3`, `blue.mp3`, `green.mp3`, `yellow.mp3`, and `wrong.mp3`) in the `sounds/` folder. These are used to play sound effects during the game.

## How to Play
1. The game will start when you press any key.
2. Watch for the sequence of colors that will flash on the screen.
3. Click the buttons in the same order as they were shown to you.
4. If you get the sequence right, the game will add another color to the sequence.
5. If you make a mistake, the game will display a "Game Over" message, flash the screen red, and play the "wrong" sound.
6. Press any key to restart the game and try again.


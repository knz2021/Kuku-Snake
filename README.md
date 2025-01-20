# KukuSnake

Overview

This is an interactive multiplication snake game where players control a snake to collect the correct answers to multiplication problems while avoiding wrong answers and collisions. The game is designed to be engaging and educational.

Features

Speed Selection: Choose between three speeds (Slow, Normal, Fast) to adjust the game's difficulty.

Responsive Design: The game canvas resizes dynamically based on the screen size.

Multiplication Questions: Players solve random multiplication problems by guiding the snake to the correct answer.

Game Over Conditions:

The snake collides with the wall or itself.

The player selects an incorrect answer.

Controls

Keyboard:

Arrow keys (↑, ↓, ←, →) to move the snake.

On-Screen Buttons:

Use the directional buttons on the screen for touch-based devices.

Touch Gestures:

Swipe in the desired direction to control the snake.

How to Play

Open the game in a web browser.

Select a speed (Slow, Normal, or Fast) using the speed selection buttons.

Use the controls to move the snake and collect the correct answer to the multiplication question displayed at the top.

Avoid incorrect answers, walls, and collisions with the snake's body.

The game ends when the snake collides with an obstacle or selects an incorrect answer.

To restart, click the "Play Again" button after a game over.

Scoring

Each correct answer adds 10 points to your score.

The current score is displayed below the multiplication question.

Setup Instructions

Download the game files (index.html) and save them to your local system.

Open the index.html file in any modern web browser to start the game.

Customization

Adjust Game Speed

The speed options are pre-configured as:

Slow: 300ms per frame

Normal: 200ms per frame

Fast: 100ms per frame

To change these values, modify the setSpeed function in the JavaScript code:

function setSpeed(speed) {
    gameSpeed = speed;  // Adjust speed value in milliseconds
    if (!gameOver) {
        clearTimeout(gameLoop);
        drawGame();
    }
}

Technologies Used

HTML: Structure of the game

CSS: Styling for the game UI

JavaScript: Game logic and interactivity

Compatibility

The game is compatible with modern web browsers, including:

Google Chrome

Mozilla Firefox

Microsoft Edge

Safari

License

This game is open-source and free to use for personal and educational purposes.

Enjoy the game and improve your multiplication skills!

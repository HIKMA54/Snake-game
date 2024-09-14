# 🐍 Snake Game
A classic Snake game implemented using JavaScript and HTML5 Canvas. Control the snake using the arrow keys, eat food to grow longer, and avoid running into walls or your own tail. How long can you survive?

🎮 Live Demo

You can try the game by cloning the repository and running it locally, or by opening the index.html file in any web browser.

📜 Table of Contents

Features

Getting Started

How to Play

Game Controls

Project Structure

Future Improvements


🚀 Features

Smooth Movement: The snake moves in a grid-based system at a steady frame rate.

Growing Snake: The snake grows in length each time it eats food.

Random Food Placement: Food is placed randomly within the grid.


Game Over Conditions:

The game ends if the snake hits the walls or its own body.

Keyboard Controls: Use the arrow keys to change the snake’s direction.

Dynamic Game Speed: Runs at a consistent 10 frames per second.


🛠️ Getting Started

Prerequisites

A modern web browser (Google Chrome, Firefox, Safari, Edge, etc.)

Installation

1. Clone the repository:
    
git clone https://github.com/HIKMA54/Snake-game

2. Navigate into the project directory:
cd snake-game

3. Open the index.html file in your web browser to start playing the game.

Alternatively, drag and drop the index.html file into your browser.

🎮 How to Play

Use the arrow keys to control the snake’s direction.

Eat the red food squares to grow longer.

Avoid crashing into the walls or into your own body.

The game will alert you when it's over, and you can refresh the page to restart.

🎮 Game Controls

Up Arrow: Move the snake up.

Down Arrow: Move the snake down.

Left Arrow: Move the snake left.

Right Arrow: Move the snake right.


📁 Project Structure

├── index.html          # The main HTML file

├── style.css           # Optional CSS file for styling (not required in basic game)

└── script.js           # The main JavaScript file that contains the game logic

Key Components:

index.html: Contains the HTML structure and the <canvas> element where the game is rendered.

script.js: Handles the game logic, including movement, food placement, collision detection, and rendering of the snake and food.

style.css (optional): You can add custom styles to enhance the UI of the game, such as adding background colors or customizing the canvas.

🛠️ Future Improvements

Score System: Implement a scoring system to track how much food the player has eaten.

Level Progression: Increase game speed as the snake grows to add more challenge.

Mobile Touch Controls: Add touch controls to make the game playable on mobile devices.

Pause and Restart: Include a pause feature and the ability to restart the game without refreshing the page.

Sound Effects: Add sound effects for actions like eating food or hitting a wall.

✨ Contributing

If you'd like to contribute to the project, feel free to submit a pull request or open an issue for any bugs or feature requests.



# TOWEROFHANOI

This project implements a basic Tower of Hanoi game using HTML, CSS, and JavaScript. It provides a simple user interface to input the number of disks and make moves. The game logic is handled in separate JavaScript files.

Project Structure
The project consists of the following files:

index.html: Main HTML file, containing the structure of the webpage.
style.css: External CSS file for styling the webpage.
hanoi.js: JavaScript file that contains the game logic for solving or handling the Tower of Hanoi problem.
tower.js: JavaScript file responsible for rendering the user interface and handling user interaction with the game.
Prerequisites
To run this project, you only need a modern web browser. No external dependencies or packages are required.

How to Use
Open the Game:

Open the index.html file in a web browser.
Input Number of Disks:

Enter the number of disks for the Tower of Hanoi puzzle into the provided input field (with id="InputNum").
Make a Move:

Press the "Make Move" button to initiate a move in the game. The makeMove() function defined in hanoi.js will be called to execute the logic of moving the disks between the towers.
Game Area:

The game display will appear in the <div> element with the id="game", where the current state of the towers will be visually rendered.

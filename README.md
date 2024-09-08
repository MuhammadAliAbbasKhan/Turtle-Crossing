Turtle Crossing Game 🐢🚗

This is a Turtle Crossing Game built using Python and the Turtle graphics library. The objective of the game is to help the turtle cross the road while avoiding oncoming cars. Each successful crossing increases the level and the speed of the cars.

Features

Player Control: Use the "Up" arrow key to move the turtle upward.
Car Traffic: Randomly generated cars drive horizontally across the screen.
Level System: Each time the turtle reaches the other side, the level increases, and the car speed gets faster.
Game Over: The game ends if the turtle collides with a car.

How to Play

Use the "Up" arrow key to move the turtle towards the top of the screen.
Avoid the oncoming cars by timing your movements.
If the turtle reaches the finish line (top of the screen), it will reset at the bottom, and the level will increase.
The game ends if the turtle hits any car.

Project Structure

├── player.py          # Contains the Player class, which manages the turtle's movement
├── car_manager.py     # Contains the CarManager class, which handles car generation and movement
├── scoreboard.py      # Contains the Scoreboard class, which keeps track of levels and displays "Game Over"
├── main.py            # Main file that runs the game logic
├── README.md          # This file

Prerequisites

Python 3.x
turtle library (pre-installed with Python)


Future Enhancements
Add more obstacles like different types of vehicles.
Implement lives and scores based on how many successful crossings the player makes.
Add sound effects for collisions and successful level-ups. 

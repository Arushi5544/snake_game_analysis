# snake_game_analysis
Comparative analysis of snake game in C and Python Programming languages

# Snake Game in C
* console-based Snake game implemented in C.
* snake.c: Main source file containing the game implementation.
## Header Files
* conio.h: Provides console input/output functions (e.g.- kbhit and getch).
* stdio.h: Standard Input/Output functions.
* stdlib.h: Standard Library functions (e.g.- rand).
* unistd.h: Contains the sleep function.

## Functions
* setup(): Initializes the game state, including the snake's starting position and random fruit placement.
* draw(): Clears the console screen and renders the game board, snake, fruit, and score.
* input(): Handles user input to control the snake's direction and quit the game.
* logic(): Manages the game logic, including snake movement, collision detection, and score updates.
* main(): Orchestrates the game loop.

## Data Structures and Algorithms
* Basic game loop for continuous execution.
* Random number generation for fruit placement.
* Simple collision detection to check for boundaries.
* Use of global variables to maintain the game state.

## Output
<img width="180" alt="image" src="https://github.com/ArushiCh/snake_game_analysis/assets/116668958/cf7ebe40-a0aa-44a0-ab43-eafe4f85ebae">

* 0--> Snake body
* *--> Food

# Snake Game in Python
A simple Snake game implemented in Python using the Pygame library.

## Description
This Snake game is a classic arcade game where the player controls a snake that must eat fruits to grow while avoiding collisions with itself and the game boundaries.

## Features
* Snake movement controlled by arrow keys.
* Fruits spawn randomly on the screen.
* Score tracking for each fruit eaten.
* Game over conditions (collisions with boundaries or self).

## Dependencies
* Python 3.x
* Pygame library

## Output

<img width="541" alt="image" src="https://github.com/ArushiCh/snake_game_analysis/assets/116668958/7ebbdd44-39d4-46fe-848a-ae3bb6045694">


  





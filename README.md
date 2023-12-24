# Main 

This Java program initializes a `GameFrame` to create a simple game window. The `GameFrame` likely contains the main game logic and user interface.

## Usage

Run the `Main` class to start the simple game.

# Table Tennis Game Frame

The `GameFrame` class in Java represents the game frame for a simple Table Tennis game. It extends the `JFrame` class and initializes a `GamePanel` for the game.

## Usage

1. Create an instance of the `GameFrame` class to start the Table Tennis game.

2. Run the program to launch the Table Tennis game window.

# Table Tennis Game Panel

The `GamePanel` class in Java represents the game panel for a simple Table Tennis game. It handles the drawing, movement, and collision detection of paddles and a ball.

## Features

- Two paddles and a ball are displayed on the game panel.
- Paddles are controlled using keyboard input.
- Collision detection ensures the ball bounces off walls and paddles.
- Keeps track of player scores.

## Usage

1. Create an instance of the `GamePanel` class to integrate it into your Table Tennis game.

2. The game runs continuously in a separate thread, handling movement and collision detection.

3. Player scores are updated when the ball passes the left or right boundaries.

# Paddle Class

The `Paddle` class in Java represents a paddle entity for a game. It extends the `Rectangle` class and includes methods for handling keyboard input to control the paddle's movement.

## Class Members

- **id**: An integer representing the ID of the paddle (1 or 2).
- **yVelocity**: The vertical velocity of the paddle.
- **speed**: The speed at which the paddle moves.

# Ball Class

The `Ball` class in Java represents a ball entity for a game. It extends the `Rectangle` class and includes methods for controlling the ball's movement and drawing it on the screen.

## Class Members

- **random**: An instance of the `Random` class for generating random values.
- **xVelocity**: The horizontal velocity of the ball.
- **yVelocity**: The vertical velocity of the ball.
- **initialSpeed**: The initial speed of the ball.

# Score Class

The `Score` class in Java represents the scorekeeping for a game. It extends the `Rectangle` class and includes methods for drawing player scores on the screen.

## Class Members

- **GAME_WIDTH**: Static variable representing the width of the game window.
- **GAME_HEIGHT**: Static variable representing the height of the game window.
- **player1**: Integer storing the score of player 1.
- **player2**: Integer storing the score of player 2.














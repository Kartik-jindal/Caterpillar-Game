# Snake Game with Turtle Graphics

This Python script implements a simple snake game using the Turtle graphics library. The game features a caterpillar controlled by arrow keys, aiming to eat green leaves to grow longer. The game ends if the caterpillar collides with the window boundaries.

## Instructions:

1. Press the **SPACE** key to start the game.
2. Use the arrow keys to control the caterpillar:
   - **UP** arrow: Move upward
   - **DOWN** arrow: Move downward
   - **LEFT** arrow: Move leftward
   - **RIGHT** arrow: Move rightward
3. The caterpillar grows longer by eating green leaves, earning points with each leaf consumed.
4. Avoid hitting the window boundaries, as it will end the game.
5. To restart the game after it's over, press the **UP** arrow key.

## Dependencies:
- Turtle graphics library (built-in with Python)

## How to Run:
1. Clone the repository or download the Python script.
2. Run the script in a Python environment.

## Gameplay:
- The caterpillar's speed and length increase with each leaf consumed.
- The score is displayed in the top-right corner of the window.
- When the game ends, press the **SPACE** key to restart.

## Code Explanation:

The code is structured into several sections:

1. **Initialization:** Setting up the Turtle screen, caterpillar, leaf, and initializing game variables.

2. **Game Functions:**
   - `outside_window()`: Checks if the caterpillar is outside the window boundaries.
   - `game_over()`: Displays a game over message and allows restarting with the **SPACE** key.
   - `display_score()`: Updates and displays the current score.
   - `place_leaf()`: Randomly positions a new leaf on the screen.
   - `start_game()`: Initiates the game loop, handling collisions, scoring, and caterpillar growth.

3. **Movement Functions:**
   - `move_up()`, `move_down()`, `move_left()`, `move_right()`: Functions to change the caterpillar's heading.

4. **Event Handling:**
   - Defines key events to start the game, restart it, and control caterpillar movement.

## How to Contribute:
- Fork the repository.
- Make enhancements or fix issues.
- Create a pull request.
# Author
Kartik Jindal

Contact: kartikjindal2003@example.com

Enjoy playing the snake game! 🐍

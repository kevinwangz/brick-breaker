# break-out

Brick Breaker
-------------

Code available upon request.

Instructions:
-------------
Use the left and right arrow keys to move the paddle.
Use the space bar to launch the ball (and start the game).
Press 'q' to exit the game. This will count as a loss.
Click anywhere on the screen to start the game.

Running the Game
-------------
`gradle -jar break-out.jar <frame rate> <ball speed>`

The first parameter controls the frame rate (20-100).
The second parameter controls the speed of the ball. Here, 1 corresponds to slow, 2 corresponds to moderate speed and 3 corresponds to fast.

The Game
-------------
- A randomly selected set of blocks is configured each time a game is started
- The player has 3 lives to remove all blocks from the screen

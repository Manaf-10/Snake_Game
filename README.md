Snake Game
Date: [30/06/2025]
By: [Manaf Hujairi]
Description
A snake game where the player controls a snake that eats a ball to grow longer and earn points. If the snake's head collides with its own body, the player loses, and the level resets.

Technologies Used
JavaScript
HTML
CSS
Pseudocode
Initialize Game Variables:

Create game board
Define game size
Initialize snake, ball, and score variables
Create Game Board:

Loop through board size
Create cells with alternating colors
Append cells to the game board
Initialize Snake:

Create snake head and body segments
Set initial position for the snake head
Spawn Ball:

Randomly generate a position for the ball
Ensure the position is empty and not where the snake starts
Game Loop:

Set up key event listeners for movement (WASD and arrow keys)
Store the last direction of movement
Continuously update the snake's position based on last direction
Check for collisions:
If snake head collides with body, call gameLost()
If snake head reaches ball, increase score and spawn new ball
Move Snake:

Update head position
Move body segments to follow the head
Game Lost Function:

Reset score and snake position
Clear the game board
Update Score Display:

Show current and best scores
Screenshots
game board game menu

Future Updates
[ ] Add levels with increasing difficulty
[ ] Implement sound effects
[ ] Completed UI design
Credits
none

# Assignment-2-Modificaction-game
*Understand the Game Logic
>>Game Objective:
The player moves left and right to avoid obstacles coming down three lanes. The game ends if the player hits an obstacle.

>>How the Game Works:

Player Movement:
The player can move left or right using the arrow keys.
The player’s position is stored in a variable x (0 = left, 1 = middle, 2 = right).

Obstacle Movement:
Obstacles appear randomly in one of the three lanes.
They move down the screen step by step.

Drawing the Game:
Each frame, the screen is cleared and redrawn with the player and obstacle in their current positions.

Collision Detection:
If the player and obstacle are in the same lane when the obstacle reaches the bottom, the game ends.

Game Speed:
The game loop waits a short time (Sleep(120)) between frames to control speed.

>>Logic Summary:
The game uses a loop to keep updating the screen, moving obstacles, and checking for collisions until the player loses.
Player input and random obstacle generation make the game interactive and challenging.


*Implementation of modifications

>>Features Added:

<<Score Card:
The game now keeps track of how many obstacles the player successfully avoids.
Each obstacle avoided increases your score by 1.

<<Player Lives:
You now have 3 lives instead of the game ending on first collision.
Each time you hit an obstacle, one life is lost.
Game ends when all lives are lost.

<<Difficulty Levels:
The game speed increases as your score increases, making it more challenging.
Every 5 points, obstacles fall faster.

>>How to Play:
Use LEFT and RIGHT arrow keys to move the player between lanes.
Avoid obstacles coming down the lanes.
Watch your score and lives at the bottom.

>>Logic Behind Changes:
score variable tracks progress.
lives variable allows multiple tries.
speed variable makes game progressively harder as you do better.


(I tried adding simple features which I could do on my own with my basic understanding of loops and functions.)
    Hope you enjoy to play it!!!


(I couldn't add the forked repository because of some issue on my git installation. So,I added the file by just copy and pasting it from the source...Hope it is right!! )
Thanks!!!!!!!!!!!!!!!





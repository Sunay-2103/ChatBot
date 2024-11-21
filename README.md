This is a simple snake game made using Python 3.12
3 libraries are used in this code sample, pygame, time and random.
Pygame - Library which is used for creating games and mainly their game window and movements.
Time - Is used for updating the game at a constant speed to ensure the game runs comfortably
Random - Is used to generate food at random places (x,y)
draw_snake , message and game_loop are the 3 major functions used
Draw Snake is used to draw the snake in the form of black blocks which are incremented after every food item is eaten
Message is used to simply react with the user once the game ends and takes you to a blue screen where you can press C or Q to start again 
Game loop is run whenever the loop is evaluated to true and terminates once game_end is equal to False.
Clock tick is an interesting function which is used to reduce the game speed to run it smoothly if the game speed exceeds the speed if the game initially
Each pixel is of a size of 10 ptx and the window is a 600 width by 400 length window .

# DotsAndBoxes
A game of dots and boxes in C++ for two players, to be locally played on the terminal.

## How To Play
Player A and B alternate turns, with Player A always starting first. The game will print out whose turn it is.    
On your turn, type in the row and column that you would like to draw a line, and which direction.   
For example, "0 0 H" draws a horizontal line from the top-left dot that is one box long, and "0 0 V" draws a vertical line from the top-left dot downwards, that is one box long.   
Please provide valid input. If that line is already drawn or it does not exist, you will be prompted to try again.   
When one box has been completed, meaning that all four sides are closed off, that box now belongs to the player that drew the closing line. That player also gets to draw another line.    
      
The game continues in this fashion until all boxes have been filled. Then the score will be calculated and the game can be restarted or the player can quit.     

## Game Setup
You must specify the size of the board before playing. This can be changed every time a game is restarted.   
Type in two numbers, one for width and one for height. For example, "3 3" is a 3x3 grid, while "4 5" is a grid 4 across and 5 tall.   
Then the game can begin.    
   
The game board must be a minimum of a 2x2 board and a maximum of a 10x10 board, where 2x2 means that two lines or three dots can be drawn per row and column.   

## Commands
Q - quit game    
R - restart game   
X_COORD Y_COORD DIRECTION - draw a line starting from that dot, in that direction (H or V)   
WIDTH HEIGHT - set up a board of WIDTH dots wide and HEIGHT dots tall.   
   
Thank you for playing!

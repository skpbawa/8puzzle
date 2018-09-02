Game : 

This is a simple puzzle game invloving a 3*3 box shown on a webpage.
There are numbers marked 1 to 8 in 8 cells while one cell is empty.
Empty cell can be moved in required direction by clicking on the cell where we want it to move.
We need to achieve a final state where first cell is having 1, 2nd is having 2 and so on.
The game finishes then.
I have also implemented the AI solver for this game which tells you the next move when you are stuck and
completes the game for you.


Algo
-------------
The game is designed in PHP. The matrix is just a form which gets submitted when you click.
The submitted form is processed and new form is generated and shown to you.
I have used Sessions variables to achieve this.
The AI algorithm first find the position of a particular number and then moves are generated to achieve that.
I take care that previous right positioned numbers are not misplaced while placing wrong placed numbers at 
right positions.
The algorithms is divided into 3 parts for different kinds of movements:
    General Movement
    Special Movement
    Deadlock Movement

The code is clear enough to understand it.
I have avoided comments and naming is clear to tell the purpose of each line.

Thanks!

# Prize-Maze
A computer program in C++ to show how a maze can be traversed efficiently to collect prizes.

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
x £ xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
xxxxxx xx xxxxxx £ £ xxxx
xxxxxx xx xxxxxxxxxxxxxxxxx xxxxxxxxxxxx
xxxxxx xx xxxxxxx£xxxxxxxxx xxxxxxxxxxxx
xxxxxx xx xxxxxx            xxxxxxxxxxxx
xxxxxx xx xxxxxxxxxxxxxxxxx xxxxxxxxxxxx
xxxxxx xx £ xxxxxxxxxxxx
xxxxxx xxxxxxxxxxxxxxxxxx xxxxxxxxxxxxxx
xxxxxx xxxxxxxxxxxxxxxxxx xxxxxxxxxxxxxx
xxxxxx xxxxxxxxxxxxxxxxxx £ xxxxxx
xxxxxx xxxxxxxxxxxxxxxxxx xxxxxxxxxxxxxx
xxxxxx xxxxxxx £ xxxxxxxxxxxxxx
xxxxxx xxxxxxxxxxxxxxxxxx £ xxxxx
xxxxxx xxxxxxxxxxxxxxxxxx xxxxxxxxxxxxxx
xxxxxx xxxxxxxxxxxxxxxxxx xxxxxxxxxxxxxx
xxxxx £                                P
xxxxxx xxxxxx xxxxxxxxxxx xxxxxxxxxxxxxx
xxxxxx xxxxxx xxxxxxxxxxx£xxxxxxxxxxxxxx
xxxxxx £ xx xxxxxx xxxx xxxxxxxxxxxxxx
xxxxxx xxxxxx xxxxxx£xxxxxxxxxxxxxxxxxxx
x £ xxxxxx xxxxxx xxxxxxxxxxxxxxxxxxx
xxxxxx xxxxxx £ xxxxxxxxxxxxxx
xxxxxx £ xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

The Maze.txt file

The rules governing the maze
● The maze is provided as a txt file and is also shown above
○ The player is denoted as “P”
○ The prizes are denoted as “£”
○ The maze walls are denoted by “x”
○ The player moves around the maze collecting prizes
○ When a prize is collected it disappears
○ The player starts with health at 150 points
○ It costs 1 health point for a player to move 1 square
○ Each “£” awards 11 health points

The requirements of navigating the maze
● Show how the player “P” can be moved throughout the maze collecting each prize “£”
● Each player move should be shown on the screen by redrawing the maze
● Each time the maze is redrawn, show the current number of health points for the player 1
● Once the player has collected the last prize “£” they must leave the maze
● A player leaves the maze by moving to the exit
● The exit to the maze is where the player “P” started from
● When the player “P” reaches the exit the game is over
● Show the final health points of the player when the game finishes

The requirements of the path-finding algorithm
● You should attempt to derive the most efficient path to collect all prizes “£” and exit
● The health points of the player “P” indicates the efficiency of your path-finding
● The higher the health points, the more efficient your path-finding algorithm is

Learning outcomes 
● Be capable of designing and creating programs
● Realise inappropriate/appropriate usage of programming languages
● Understand how to manage memory
● To be able to:
○ create and use data structures
○ use condition statements, loops and functions
○ utilise concurrency when appropriate
○ create programs that handle run-time errors
○ use appropriate techniques for debugging and analysing existing algorithms
○ design programs using a well known methodology

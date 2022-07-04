# Navigation-route

Suppose that a house consists of a grid of N × M cells, represented like this:
....XXX
.XXX...
....X..
.X.X...
.X.X.X.
pX...X@
As you can see, the map consists of N lines (in this case, 6) and M columns (in this case, 7). Each cell of the house is marked with one of four symbols: 
"p" represents the agent’s current location, 
"X" represents a wall through which the agent cannot pass, 
"." represents open space over which the agent can fly, 
And @ represents your location.

The goal here is to write a program that finds the shortest path between the agent and me. The agent can move one square at a time in any of the four principal
compass directions, and the program should find the shortest distance between the two points and then output a string of letters (L, R, D, and U for left, right,
down, and up) indicating that solution.
For example:
Shhhh... quiet while I navigate!
Here’s the solution I found:
16 UUURRDDDRRUURRDD

You can assume that there is always exactly one p and one @ in the map file. If there is no solution, your program should display path length -1 and not display a path.

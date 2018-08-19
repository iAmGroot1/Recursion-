# Recursion
  These are a few problems I tried so as to familarize myself with recursion, a brief description of which is given below.

## Maze Problem :
 A Maze is given as N*N binary matrix of blocks where source block is the upper left most block i.e., maze[0][0] and destination(food) block is lower rightmost block i.e., maze[N-1][N-1]. A rat starts from source and has to reach the destination. The rat can move only in any direction; forward, backward, left and right
In the maze matrix, 'X' means the block is a dead end and ' ' means the block can be used in the path from source to destination.
This programme finds the shortest number of way required for the rat to reach its food (*A happy rat* :bowtie:).

## Brackets :
The problems is as such; given a number n find the number of valid possible parentheses expressions of that length.
A valid parenthesis has an equal number of open and closed parenthesis at its end and a larger or equal amount of open parenthesis than the closed ones throughout the sequence.

**Example** :


VALID | INVALID
------------ | -------------
{}{}{} | {}}{}}
{{{}}} | {{}}}{


INPUT(n) | OUTPUT
------------ | -------------
6 | 132
4 | 14


## Tower of Hanoi :
*A rather simple one*:grin:

 Tower of Hanoi consists of three pegs or towers with n disks placed one over the other. The objective is to move the stack to another peg following these simple rules:
- Only one disk can be moved at a time.
- No disk can be placed on top of the smaller disk.

This programme prints the (**minimum**)steps required to solve this puzzle. 

**Example:**

![GitHub Logo](/images.png)

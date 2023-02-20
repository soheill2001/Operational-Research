# Unique Paths

This code is a Python implementation of a recursive algorithm to find the number of possible paths from a starting point to an ending point in a 2D grid. The code can be used to solve problems such as finding the number of ways to reach a particular destination in a maze.

## Usage
To use this code, you need to have a 2D grid that represents the maze or the area in which the path should be found. The grid should be represented as a list of lists, where each element is either 0 or 1. 0 represents a free space, and 1 represents an obstacle or a blocked space.

To find the number of possible paths, you need to call the paths function, passing the following parameters:

+ `grid`: the 2D list representing the maze or the area to search for the path.
+ `x_end`: the row number of the ending point.
+ `y_end`: the column number of the ending point.
+ `x_start`: the row number of the starting point.
+ `y_start`: the column number of the starting point.

The output will be the number of possible paths.

## Limitations
The recursive algorithm used in this code can be computationally expensive for large grids, or for grids with many obstacles. As the algorithm explores every possible path, the time complexity can be exponential, making it impractical for large mazes.
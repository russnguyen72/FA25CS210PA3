# DFS Maze Solver
## CS 210 (Spring 26)

---

### Entry 1
#### Date: 2026-04-22

Today I analyzed the problem I had to solve. I got familiar with the maze generation and how mazes may look, informing me on how to best approach the problem after multiple maze generations. I then researched the behavior of DFS and specifically how it acts when solving mazes. After analyzing the problem and researching the algorithm I am using, I then implemented a small part of the algorithm. This part of the algorithm is mainly the exit detection part of the method. If the coordinates of the spot that DFS is called on equals the coordinates of the exit square, it returns true. Otherwise, it returns false.

---

### Entry 2
#### Date: 2026-04-23

I began further developing the DFS maze searching algorithm. I implemented bound and a previously visited check for when the DFS method's recursive functionality is implemented in the future. Currently, the DFS algorithm checks if the passed through coordinates are valid and if the coordinate pair has been visited. If the coordinates are not valid, or DFS is called again on any given coordinate pair, then the DFS function will return false. These are the new, additional base cases that the algorithm will check before recursing.
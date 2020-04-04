# Iterative-Deepening-Depth-first-search-algorithm
It is an algorithm which uses a limit for one cycle and infinite search until node found.

---
## Problem Statement:
The aim of the project is to create GUI, where Romania map will be taken as an
input. Apply Iterative Deepening Depth first search algorithm on Romania
map and show the solution in each step. Give a provision to select any source
and destination by the user. On clicking “SUBMIT” button, algorithm execution
will be visualized on the screen. You can use different colors to represent each
step.

---
## About Iterative Deepening:
* In computer science, iterative deepening search or more specifically iterative deepening depth-first search[2] (IDS or IDDFS) is a state space/graph search strategy in which a depth-limited version of depth-first search is run repeatedly with increasing depth limits until the goal is found. IDDFS is optimal like breadth-first search, but uses much less memory; at each iteration, it visits the nodes in the search tree in the same order as depth-first search, but the cumulative order in which nodes are first visited is effectively breadth-first.
* IDDFS combines depth-first search’s space-efficiency and breadth-first search’s fast search (for nodes closer to root).
* IDDFS calls DFS for different depths starting from an initial value. In every call, DFS is restricted from going beyond given depth. So basically we do DFS in a BFS fashion.
* Since iterative deepening visits states multiple times, it may seem wasteful, but it turns out to be not so costly, since in a tree most of the nodes are in the bottom level, so it does not matter much if the upper levels are visited multiple times.

---

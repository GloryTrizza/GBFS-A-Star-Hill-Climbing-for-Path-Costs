# GBFS-A-Star-Hill-Climbing-for-Path-Costs

This repository contains several popular Artificial Intelligence algorithms implemented in Python, including:

Greedy Best First Search
A*
Hill Climb Search

## Prerequisites
The following packages and libraries are required to run the code:
Python 3
operator

## GBFS
Greedy Best-First Search (GBFS) is a heuristic search algorithm that tries to find the optimal solution to a problem by making the locally optimal choice at each step. Unlike A* which uses a combination of heuristics and a cost function, GBFS only uses a heuristic function to estimate the distance from a given node to the goal state. The heuristic function must be admissible and consistent, meaning that it should never overestimate the cost to reach the goal state, and it should be consistent in the sense that the estimated cost should be monotonically increasing along the path from the start state to the goal state.

A* (A-Star)
A* is a search algorithm that combines the strengths of both GBFS and Dijkstra's algorithm. It uses a heuristic function to determine which vertices to explore next, allowing it to find the shortest path more efficiently than GBFS. The heuristic function estimates the cost of reaching the goal from a given vertex. A* explores vertices that are likely to lead to the goal first, making it faster than Dijkstra's algorithm, which explores all vertices without any preference.

Hill Climbing
Hill Climbing is a type of optimization algorithm used to find the local maximum or minimum of a function. It starts from an initial solution and iteratively improves the solution by making small changes. The algorithm moves in the direction of the highest increase in the value of the function and stops when there is no further improvement possible. Hill Climbing can be used for a variety of optimization problems, including finding the shortest path in a graph.

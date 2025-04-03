# ME5413_HW3

This project is part of the ME5413 Autonomous Mobile Robotics module. It focuses on the implementation and analysis of various path planning algorithms in a 2D grid environment. Specifically, simulate a shopping route at VivoCity Level 2 using occupancy grid maps and apply global planning algorithms to determine optimal travel routes.

## Project Overview

### Task 1: Global Path Planning

__Objective__: Plan paths between key locations (start, snacks, store, movie, and food) on a 1000x1000 pixel occupancy grid map (each cell = 0.2m x 0.2m).

__Main Algorithm Implemented__: A* Algorithm with 8-connected grid neighbors.

__Features__: 
 - Two different heuristic functions for A*.
 - Visualization of paths, visited nodes, and distance metrics.
 - Optional comparison with Greedy Best-First Search, Rapidly-exploring Random Tree, and Rapidly-exploring Random Tree Star algorithm.

### Task 1: The "Travelling Shopper" Problem

__Objective__: Solve a variant of the Travelling Salesman Problem (TSP) to determine the shortest route to visit all locations and return to the start.

__Methods Implemented__:
 - Brute-force permutation search.
 - Held-karp Algorithm.

## Dependencies
The project is implemented in Python using Jupyter Notebook. The following libraries are required:
 - numpy
 - matplotlib
 - opencv-python
 - time
 - heapq
 - itertools

Install dependencies via pip:
```
pip install numpy matplotlib opencv-python
```

## How to Run

1. Clone or download the repository.

```
git clone git@github.com:YukiKuma111/NUS_ME5413_Homework3_Planning.git
```

2. Open the Jupyter Notebook:

```
jupyter notebook homework3.ipynb
```

## Output

 - Planned paths overlaid on the map.

 - Travelled distance in meters.

 - Visited cells by the algorithm.

 - Runtime and performance statistics.

 - Final shortest tour for the shopping task.

A set of images are stored under `./output` for display as results.
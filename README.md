![image](https://github.com/user-attachments/assets/62dbb610-5f9d-4183-82a7-3f8a45e9967c)
# Dijkstra Algorithm - MATLAB Implementation

This project includes an implementation of Dijkstra's algorithm using MATLAB. The algorithm is used to find the shortest path between two nodes in a given weighted graph, which may be directed or undirected.

## Features

- Graph structure defined via an adjacency matrix
- Customizable start and goal nodes
- Calculates minimum cost to reach each node
- Finds and displays the shortest path step-by-step
- Informs the user if the goal is unreachable

## File Contents

- `dijkstra.m` – MATLAB script containing the main implementation of the algorithm

## How to Use

1. Open the file in MATLAB.
2. Set `startNode` and `goalNode` to desired node indices.
3. Run the code. The console will display:
   - The minimum cost to reach each node
   - The shortest path from the start to the goal node

## Example Graph

The following example adjacency matrix is used:

```matlab
A = [inf 3 2 inf inf inf inf;
     3 inf 2 4 inf inf 1;
     2 2 inf inf 1 6 3;
     inf 4 inf inf inf 1 inf;
     inf inf 1 inf inf 2 inf;
     inf inf 6 1 2 inf 2;
     inf 1 3 inf inf 2 inf];

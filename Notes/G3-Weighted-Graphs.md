# Weighted Graphs 

## Introduction
![image](https://user-images.githubusercontent.com/66233296/164998745-9ffd5e45-40ee-4e3c-9a7b-f60c0dd2f31f.png)

- When dealing with weighted graphs, traversal and connectivity algorithms usually have goal of finding not just any solution, but the best one with respect to weights, where weights represent non-negative costs:
  - Shortest Paths: find minimum cost path from A to B, or from A to anywhere (single-source shortest path tree), or single-sink, or anywhere to anywhere (all-source, all-sink)
  - Trees: find the minimum spanning tree (MST), with minimum total cost among chosen edges.


## Priority Queues 
![image](https://user-images.githubusercontent.com/66233296/164998845-faf07b13-d360-4677-8aed-55aaaa3fd451.png)

## Heap
![image](https://user-images.githubusercontent.com/66233296/164998953-5d065377-c6ab-4173-aed0-9421463fa2b0.png)

## Priority Queues' applicaitons
![image](https://user-images.githubusercontent.com/66233296/164999139-8bbcb04d-1053-4c49-a9e3-dbafd58c2d3b.png)

## Prim/Dijkstra
-Prim and Dijkstra independently presented nearly the same algorithm (differing basically by a single line) for solving MST (Prim) and Shortest path tree (Dijkstra) problems. 

- The objective of the algorithm is to find the shortest path between any two vertices in a graph
![image](https://user-images.githubusercontent.com/66233296/165000304-99c0f37b-daa3-4629-9b46-ece2aad7e245.png)
![image](https://user-images.githubusercontent.com/66233296/165000308-b65f484c-ab7d-45c7-9b6d-b71a0d2076b7.png)
![image](https://user-images.githubusercontent.com/66233296/167976233-6a084030-521e-4b72-a80a-683a0c09f095.png)


- Dijkstra algorithm -->
[Video explains the algorithm  ](https://www.youtube.com/watch?v=pVfj6mxhdMw)


## Minimal Spanning Trees
- Go through the whole graph then pick up the edges (the lightest weight edge comes first)
- Make sure the edges picked up won't form a cycle



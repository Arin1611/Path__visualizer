# PathFindingVisualizer
Website to see visualizations of different path finding algorithms

## Algorithms

### Dijkstra :
  - A path-finding and graph traversal algorithm.
  - Works on both weighted and unweighted graphs.
  - Get the shortest path from start node to end node by calculating the weight cost of visiting each neighbouring node.
  - Has disadvantage compared to A* because it finds the shortest path with greater number of nodes being visited.

  


---
### Breadth first search :
  - A graph traversing algorithm where from starting node each neighbouring node is visited that has not been visited yet. The neighbouring node at current breadth or layer are      visited first from which the remaining nodes are traversed.
  - Disadvantage is it cannot work for weighted graphs.

   



---
### A* :
  - An informed path-finding and graph traversal algorithm.
  - Can find the shortest path with less number of nodes visited compared to BFS and dijkstra.
  - Works in both weighted and unweighted graph and at each stage of discovering a node it calculates the shortest path from the current node to end node.
  - The shortest path is calculated by f_score where f_score = g_score + h_score.
  - g_score : The weighted distance from start node to the current node.
  - h_score : The estimated cost of movement from current node to end node. Manhattan distance is used here to calculate the h_score.
  



---
### Depth first search :
  - A graph traversing algorithm
  - From the name it can be identified that this algorithm traverses to the depth of a node
  - From a given node the algorithm will got deep discovering all the neighbouring nodes at the depth and backtrack when no further nodes are needed to be discovered
  - Doesn't guarantee shortest path

   




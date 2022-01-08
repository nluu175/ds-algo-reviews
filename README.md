# Topics

## Graphs

- A Graph consists of a finite set of vertices(or nodes) and set of Edges which connect a pair of nodes.
- For example, the set of vertices V = {0,1,2,3,4} and the set of edges E = {01, 12, 23, 34, 04, 14, 13}.
- There are directed and undirected graphs.
- Keywords: Vertex, Edge, Adjacency, Path.

### Algorithms

- Need to know both recursive and iterative implementaion for BFS and DFS.
- BFS and DFS are algorithms used for tree traversal on graphs or tree data structures.

#### Breadth-first search (BFS) - bfs.py

1. Pick any node, visit the adjacent unvisited vertex, mark it as visited, display it, and insert it in a queue.
2. If there are no remaining adjacent vertices left, remove the first vertex from the queue.
3. Repeat step 1 and step 2 until the queue is empty or the desired node is found.

- Time complexity is O(V + E)

#### Depth-first search (DFS) - dfs.py

1. Pick any node. If it is unvisited, mark it as visited and recur on all its adjacent nodes.
2. Repeat until all the nodes are visited, or the node to be searched is found.

- Time complexity is O(V + E)

#### Comparision

- https://www.guru99.com/difference-between-bfs-and-dfs.html
- https://www.geeksforgeeks.org/difference-between-bfs-and-dfs/

- BFS finds the shortest path to the destination whereas DFS goes to the bottom of a subtree, then backtracks.
- BFS traverses according to tree level while DFS traverses according to tree depth.
- In BFS, you can never be trapped into finite loops whereas in DFS you can be trapped into infinite loops.

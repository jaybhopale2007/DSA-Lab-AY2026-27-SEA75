# Practical No. 9

## Title
Graph Traversal for Campus Navigation Using BFS and DFS

## Algorithm

1. **Start**
2. Define the number of buildings and represent them as vertices of the graph.
3. Create an adjacency matrix to represent connections between buildings.
4. Enter the connections between the buildings in the adjacency matrix.
5. Select the starting building.
6. **For BFS:**

   * Initialize a queue and a `visited` array.
   * Mark the starting building as visited and insert it into the queue.
   * Remove a building from the queue and display it.
   * Check all adjacent buildings.
   * If an adjacent building is not visited, mark it visited and insert it into the queue.
   * Repeat until the queue becomes empty.
7. **For DFS:**

   * Initialize a `visited` array.
   * Mark the starting building as visited and display it.
   * Check all adjacent buildings.
   * If an adjacent building is not visited, recursively perform DFS on it.
   * Continue until all reachable buildings are visited.
8. Display the BFS and DFS traversal results.
9. **Stop**.

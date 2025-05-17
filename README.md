The A* (A-star) algorithm is a popular pathfinding and graph traversal algorithm. It is widely used in applications like:

- Game development (for AI pathfinding)

- Robotics (navigation)

- Network routing

- Map-based route planning (e.g., Google Maps)<br>

🔍 What is A* trying to do?
- A* finds the shortest path between a start node and a goal node in a graph while minimizing cost (e.g., time, distance, energy, etc.).

- It improves on Dijkstra's algorithm by using heuristics to guide the search.



🧠 Core Idea

> A* selects the next node to explore based on:

    f(n)=g(n)+h(n)

Where:

- g(n): cost from the start to node 
  
- h(n): estimated cost from node n to the goal (this is the heuristic)
  
- f(n): total estimated cost of the cheapest path through n

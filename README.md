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

--------------------------------------------------------------------

🪙 Greedy Algorithm

The Greedy Algorithm is a popular optimization strategy in computer science and mathematics. It is commonly applied in:

- Resource selection and scheduling (e.g., Huffman coding)

- Scheduling problems

- Knapsack problem

- Set cover problem

- Network design (e.g., Minimum Spanning Tree, Dijkstra...)

🔍 What is Greedy trying to do?
The Greedy algorithm builds up a solution step by step, always choosing the best option available at the moment, hoping that these local optimum choices will lead to a global optimum solution.

🧠 Core Idea
Greedy works under the principle:

- At each step, pick the best possible option without reconsidering previous decisions.

- Unlike A* or Dynamic Programming, Greedy does not backtrack or revise its choices.

📌 Key Characteristics
- Fast and simple

- Doesn't always yield the optimal solution unless the problem satisfies:

- The Greedy-choice property

- Optimal substructure

📦 Classic Examples
- Prim's/Kruskal's Algorithm (for Minimum Spanning Tree)

- Dijkstra's Algorithm (for shortest path with non-negative weights)

- Coin change problem (if denominations are suitable)

- Huffman encoding

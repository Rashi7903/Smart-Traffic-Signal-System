# Smart-Traffic-Signal-System
## Overview
The **Smart Traffic Signal System** is a project designed to optimize traffic flow using **Dijkstra's Algorithm**. It calculates the shortest path between nodes (representing traffic junctions) to ensure efficient routing, minimizing travel time and handling variable road conditions.

## Features
- **Dijkstra's Algorithm**: Finds the shortest path between unvisited nodes, continuously updating the shortest distance from the starting point.
- **Traffic Management Benefits**:
  - Guarantees the shortest path for vehicles.
  - Efficient for traffic routing.
  - Handles variable road conditions (e.g., traffic density, roadblocks).
- Visual representation of nodes (junctions) and paths with weighted edges (distances).

## How It Works
1. The system represents traffic junctions as nodes (A to I) and roads as edges with weights (distances).
2. Using Dijkstra's Algorithm, it calculates the shortest path from a starting node (e.g., A) to a destination node (e.g., I).
3. The current path is displayed (e.g., A → D → E → H → I).

### Example
- **Starting Node**: A
- **Destination Node**: I
- **Path**: A → D → E → H → I
- **Graph Representation**:
  - Nodes: A, B, C, D, E, F, G, H, I
  - Edges with weights (distances):
    - A → B: 4
    - A → D: 3
    - B → C: 3
    - B → E: 5
    - C → F: 2
    - D → E: 2
    - D → G: 4
    - E → F: 4
    - E → H: 3
    - F → I: 5
    - G → H: 2
    - H → I: 6

## Installation
1. Download the Bolt project file: `project-bolt-sb1-pavexwy5.zip` from this repository.
2. Open the file in the Bolt app to interact with the Smart Traffic Signal System.
3. Use the Bolt to GitHub extension to sync and manage updates (if applicable).

## Usage
- Open the project in Bolt.
- Click the "Dijkstra" button to run the algorithm and find the shortest path.
- Use the "A* Algorithm" button to compare results with an alternative pathfinding method.
- The current path will be displayed at the bottom of the interface.

## Contributing
1. Fork this repository.
2. Clone the forked repository to your local machine.
3. Make changes or improvements to the project.
4. Commit and push your changes.
5. Create a pull request to contribute to this project.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

# Path Finding Algorithms Projects
## A* Algorithm for Pathfinding in a Maze  

## 📌 Project Overview  
This project implements the **A\* Algorithm**, a powerful pathfinding and graph traversal algorithm, to navigate through a maze. The algorithm efficiently determines the shortest path from a starting point to a goal by combining actual distance traveled (g-score) and heuristic estimates (h-score).  

The project demonstrates practical applications of pathfinding algorithms, such as robotics, AI navigation, and game development.  

---

## 🎯 Key Features  
- **Maze Simulation**: A dynamically generated maze where the A\* algorithm is applied.  
- **Pathfinding Visualization**: Highlights the optimal path from the start to the goal.  
- **Efficient Algorithm**: Combines cost and heuristics to ensure the shortest path is found quickly.  
- **Backward to Forward Path Conversion**: Implements a robust method to calculate and visualize the path.  

---

## 🔧 Technologies Used  
- **Programming Language**: Python  
- **Libraries**:  
  - [pyamaze]for maze generation and visualization.  
  - `PriorityQueue` from Python's standard `queue` module for managing open nodes.  

---

## 📚 How It Works  
1. **Maze Generation**: A maze is created with a defined number of rows and columns.  
2. **A\* Algorithm**:  
   - Starts from the bottom-right corner of the maze and moves towards the top-left corner.  
   - Uses a combination of g-score (actual cost) and h-score (heuristic) to explore and prioritize nodes.  
   - Finds the shortest path by breaking ties between nodes using heuristics.  
3. **Visualization**:  
   - The algorithm traces the computed path and visualizes it on the maze using the `pyamaze` library.  

---

## 📂 Project Structure  
```plaintext
├── A Star Algorithem.py              # Main script to execute the A* algorithm and visualize the path.
├── README.md            # Project documentation.



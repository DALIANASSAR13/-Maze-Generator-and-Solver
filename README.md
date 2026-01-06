# Maze Generator and Solver (Python)

## Overview

This project is a Python-based **Maze Generator and Solver** developed to demonstrate and compare classical and heuristic pathfinding algorithms. The system generates valid mazes and solves them while visualizing the process in real time, making it suitable for educational and algorithm-analysis purposes.

## Features

* Random maze generation with guaranteed solvability
* Multiple maze-solving algorithms:

  * Depth-First Search (DFS)
  * Dijkstra’s Algorithm
  * A* Search Algorithm
  * Dynamic Programming
  * Dead-End Fill
* Real-time visualization using the `turtle` graphics module
* Modular design for easy algorithm comparison and performance evaluation
* Simple frontend integration for enhanced usability and visuals

## Technologies Used

* **Language:** Python
* **Visualization:** Turtle Graphics Module
* **Algorithms:** DFS, Dijkstra’s, A*, Dynamic Programming, Dead-End Fill

## Project Structure

```
maze-generator-solver/
│-- generator.py        # Maze generation logic
│-- solver.py           # Pathfinding algorithms
│-- visualization.py    # Turtle-based visualization
│-- utils.py            # Helper functions
│-- main.py             # Application entry point
```

## How It Works

1. The maze generator creates a grid-based maze with walls and paths.
2. A selected algorithm explores the maze to find a path from the start to the goal.
3. The solving process is visualized step by step to show algorithm behavior and efficiency.

## Educational Value

This project helps in understanding:

* Graph traversal techniques
* Differences between uninformed and informed search algorithms
* Algorithm performance and optimality
* Visualization of abstract algorithmic concepts


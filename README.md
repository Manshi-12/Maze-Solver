# 🧩 Maze Solver in Java

This Java project generates and solves random mazes using a depth-first search algorithm, with real-time visual feedback via a Swing GUI. It continuously creates and solves mazes, demonstrating the solving process step by step.

## Features

- Random maze generation
- Real-time maze solving using DFS
- Swing-based GUI with animated visualization
- Color-coded maze states (walls, path, visited, empty)

## How It Works

- The maze is represented as a 2D grid of cells.
- Walls and corridors are created using a randomized algorithm.
- The solver starts from the upper-left corner and finds a path to the lower-right.
- Once a maze is solved, the program waits briefly and generates a new one.

## Getting Started

### Requirements

- Java JDK 8 or higher

### Running the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/Manshi-12/Maze-Solver.git
   ```

2. Compile the code:
   ```bash
    javac Maze.java
   ```
3. Run the program:
   ```bash
   java Maze
   ```

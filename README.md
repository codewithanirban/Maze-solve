# Maze Solver: BFS and DFS

Welcome to the Maze Solver project! This repository contains implementations of two fundamental graph traversal algorithms, Breadth-First Search (BFS) and Depth-First Search (DFS), to solve maze problems. These algorithms are used to find paths from a start point to an end point within a maze, demonstrating their practical applications in pathfinding and AI.

![dfsvsbfs](https://github.com/codewithanirban/Maze-solve/assets/155054558/11b53480-9f39-425d-89eb-60368f7be570)


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Running the Solver](#running-the-solver)
  - [Input Format](#input-format)
  - [Output Format](#output-format)
- [Algorithms](#algorithms)
  - [Breadth-First Search (BFS)](#breadth-first-search-bfs)
  - [Depth-First Search (DFS)](#depth-first-search-dfs)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a simple and clear implementation of BFS and DFS algorithms to solve mazes. It is designed for educational purposes, demonstrating how these algorithms can be used to navigate through a maze from a specified start point to an end point.

## Features

- **BFS Implementation**: Ensures the shortest path is found (if one exists).
- **DFS Implementation**: Explores as far as possible along each branch before backtracking.
- **Customizable Input**: Supports custom maze definitions via text files.
- **Visual Representation**: Outputs the path found in a visual format.

## Installation

To run this project, you need Python installed on your machine. Follow the steps below to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/maze-solver.git
   cd maze-solver
   ```

2. (Optional) Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the Solver

To run the maze solver, use the following command:
```bash
python maze.py maze1.txt
```

### Input Format

The maze input should be provided in a text file with the following format:
- `A` denotes the start point.
- `B` denotes the end point.
- `#` denotes walls.
- ` ` denotes open paths.

Example `maze.txt`:
```
#######
#A#   #
# # # #
# # #B#
#     #
#######
```

### Output Format

The output will display the maze with the path from start to end marked with `*` if a path is found.

Example output:
```
#######
#S#***#
#.#*#*#
#.#*#E#
#*****#
#######
```

## Algorithms

### Breadth-First Search (BFS)

BFS explores the maze level by level, ensuring the shortest path is found. It uses a queue to manage the nodes to be explored next.

### Depth-First Search (DFS)

DFS explores as far as possible along each branch before backtracking. It uses a stack (or recursion) to manage the nodes.

## Examples

Run BFS on a sample maze:
```bash
python maze.py maze1.txt
```

Run DFS on a sample maze:

Simply go to the maze.py file and uncomment out the commented code and it will run the DFS code.
```bash
python maze.py  maze1.txt
```

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to explore, modify, and use the code to better understand BFS and DFS algorithms. If you have any questions or suggestions, please open an issue or reach out directly.

Happy coding!

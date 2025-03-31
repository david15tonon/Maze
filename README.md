# Maze

A funny maze solving program using Depth First Search (DFS) Algorithm.

## Overview
This project is a modified version of the original maze solving program from the CS50 course at Harvard University. The program reads a maze from a text file and solves it using the Depth First Search algorithm.

## Getting Started

### Prerequisites
- Python 3.x

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/maze.git
   ```
2. Navigate to the project directory:
   ```sh
   cd maze
   ```

### Usage
To run the maze solver, use the following command:
```sh
python maze.py maze1.txt
```
You can change the maze by replacing `maze1.txt` with another maze file, such as `maze2.txt`:
```sh
python maze.py maze2.txt
```

## Example
Here is an example of how to run the program with a specific maze file:
```sh
python maze.py maze1.txt
```

## How It Works
The program reads the maze structure from the specified text file and uses the Depth First Search algorithm to find a path from the start to the end of the maze. The maze file should be formatted with the following symbols:
- `#`: Wall
- ` `: Path
- `S`: Start
- `E`: End

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [CS50](https://cs50.harvard.edu) - Original course material
- [Harvard University](https://www.harvard.edu)

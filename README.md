# Tower of Hanoi Solver

This Python script solves the Tower of Hanoi problem using both Depth-First Search (DFS) and Breadth-First Search (BFS) approaches.

## Features

- **DFS Approach:** Recursive solution for the Tower of Hanoi problem.
- **BFS Approach:** Solution using a breadth-first search strategy.

## Code Structure

- `tower_of_hanoi.py`: Contains the main code for the Tower of Hanoi solver.

### DFS Approach

- **`tower_of_hanoi_dfs(n, source, auxiliary, destination)`**
  - Recursively solves the Tower of Hanoi problem.
  - Moves discs from the source peg to the destination peg using an auxiliary peg.

### BFS Approach

- **`tower_of_hanoi_bfs(n, source, destination)`**
  - Utilizes a breadth-first search strategy to find the optimal solution.
  - Uses a State class to represent the state of the pegs at each step.

## How to Run

1. Clone the repository: `git clone https://github.com/yourusername/tower-of-hanoi.git`
2. Navigate to the project directory: `cd tower-of-hanoi`
3. Run the script: `python tower_of_hanoi.py`

## Usage

1. Enter the number of discs when prompted.
2. The script will output the steps taken to solve the Tower of Hanoi problem using both DFS and BFS approaches.

## Example

```bash
Enter the number of discs: 3

BFS Approach:
Move disc 1 from A to C
Move disc 2 from A to B
Move disc 1 from C to B
Move disc 3 from A to C
Move disc 1 from B to A
Move disc 2 from B to C
Move disc 1 from A to C

DFS Approach:
Move disc 1 from A to C
Move disc 2 from A to B
Move disc 1 from C to B
Move disc 3 from A to C
Move disc 1 from B to A
Move disc 2 from B to C
Move disc 1 from A to C

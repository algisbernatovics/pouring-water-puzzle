# Pouring Water Puzzle

A PHP command-line solver for the classic two-vessel water pouring puzzle.

## Learning Goal

Practice modeling a puzzle as a graph of states and using breadth-first search to find the shortest solution.

## Problem

Given two vessel capacities `a` and `b`, find the minimum number of operations needed to measure exactly `c` units of water. Supported operations are fill, empty, and pour between vessels.

## Approach

Each state is `(first_vessel_amount, second_vessel_amount)`. The solver explores all valid next states with BFS and returns the first step count that reaches the target.

## Complexity

- Time: `O(a * b)` in the bounded state space.
- Space: `O(a * b)` for visited states and the BFS queue.

## Example

```text
Input
1
3
5
4

Output
6
```

## Tech Stack

- PHP
- `SplQueue`
- Breadth-first search

## Run

```bash
php app/water_vessels.php
```

## Project Structure

- `app/water_vessels.php` - BFS solver and CLI input handling

## License

MIT License. See [LICENSE](./LICENSE).

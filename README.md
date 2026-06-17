# Pouring Water Puzzle

A PHP command-line solver for the classic two-vessel water pouring puzzle.

## Overview

A PHP command-line solver for the classic two-vessel water pouring puzzle.

## Features

- Calculates the minimum number of steps to reach a target amount.
- Models fill, empty, and pour actions as state transitions.
- Uses breadth-first search with visited-state tracking.

## Tech Stack

- PHP
- SplQueue
- Breadth-first search

## Project Structure

- `app/water_vessels.php` - BFS solver and CLI input handling

## Getting Started

Run with PHP:

```bash
php app/water_vessels.php
```

Input starts with the number of test cases, followed by vessel capacities and target value.

## Portfolio Notes

- Shows graph-search thinking on a constrained state-space problem.
- Keeps the core solver readable in a single file.

## Status

Portfolio-ready algorithm exercise.

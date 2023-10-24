# Repository Overview

Welcome to the repository overview! This repository serves as a collection of Jupyter notebooks and related content. It's a dynamic space where I'll continue to add various types of content for learning, experimentation, and reference.

## Contents

1. Atelier 1 : Simple and Multiple Linear Regression
- **Introduction**: Introduces simple and multiple linear regression for predicting sales.
- **Data Overview**: Provides an overview of the dataset, including data types and summary statistics.
- **Data Visualization**: Visualizes the relationship between advertising budgets and sales.
- **Training and Testing**: Demonstrates data splitting for training and testing.
- **Linear Regression**: Shows how to perform linear regression using batch gradient descent.
- **Model Evaluation**: Explains how to calculate model error (MSE) on the test data.
- **Cross-Validation**: Demonstrates k-fold cross-validation for model evaluation.
- **Comparison**: Compares the model error and cross-validation mean MSE.
- **Conclusion**: Discusses results and potential model improvements.

2. A Star Search : A* Search Algorithm (ASS)
- This code snippet represents the A* Search Algorithm. It finds the shortest path from an initial state to a goal state in a graph or grid using a heuristic estimate and a successor function. It maintains open and closed sets, explores successors, and returns the optimal path or failure if the goal cannot be reached.

3. Heuristic Search : Generic Heuristic Search (GHS)
- The code defines a generic heuristic search algorithm using A* (A Star) for finding the shortest path in a graph. It utilizes a priority queue (heap) and a `Node` class to represent nodes in the search. The algorithm starts with an initial state and iteratively explores successors, considering both the cost to reach the current node (`g`) and a heuristic estimate of the cost to reach the goal (`h`). It returns the path from the initial state to the goal state or `None` if no path is found.

4. RDLS & IDDFS : Recursive Depth-Limited Search (RDLS) & Iterative Deepening Depth-First Search (IDDFS)
#### Recursive Depth-Limited Search (RDLS)
- Finds a node with a given value using a depth-limited recursive algorithm.
- **Parameters:**
  - `xnode` (Node): the starting node for the search.
  - `goal` (object): the value to search for.
  - `limit` (int): the maximum depth to search.
- **Returns:**
  - `True` if the goal value is found within the specified depth limit, `False` otherwise.
#### Iterative Deepening Depth-First Search (IDDFS)
- Implements an iterative deepening depth-limited search algorithm to find a goal node in a tree.
- **Parameters:**
  - `node` (Node): the starting node for the search.
  - `goal` (object): the value to search for.
- **Returns:**
  - A message indicating whether the goal node was found within the specified depth limit:
    - "The goal node was successfully found :)" if found.
    - "The goal node was not found within this depth limit :(" if not found.
#### Node class
- Defines a Node class with attributes `value` and `children`.
#### Test tree
- Provides a function to build a test tree with nodes and child relationships.
#### Main program
- Builds a test tree and searches for a goal node using the IDDFS algorithm. If found, it prints "The goal node was successfully found :)."

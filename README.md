# 🤖 AI Search and Optimization Algorithms

This repository contains a practical implementation of several fundamental Artificial Intelligence (AI) algorithms, focusing on graph search and optimization techniques. This project was completed as a practical exercise in AI.

## 📝 Project Overview

This project is divided into three main parts:

1.  **Classic Graph Search:** Implementation of unweighted graph search algorithms (DFS and BFS).
2.  **Heuristic Search:** Implementation of A* search on weighted graphs.
3.  **Optimization Algorithms:** Solving the NP-hard Subset Sum problem using Hill-Climbing, Genetic Algorithms, and Brute Force search.

---

## 🚀 Algorithms Implemented

### Part 1: Graph Search Algorithms

Implementations of famous graph search algorithms on randomly generated graphs.

* **Depth-First Search (DFS):** A standard implementation of the DFS algorithm for graph traversal.
* **Breadth-First Search (BFS):** A standard implementation of the BFS algorithm for finding the shortest path in unweighted graphs.

### Part 2: Weighted Graph Search (A*)

This section extends the search to weighted graphs, where traversing each vertex has an associated cost.

* **A\* Search:** Implementation of the A\* heuristic search algorithm to find the minimum cost path from a start to a goal node.

### Part 3: Optimization for the Subset Sum Problem

This part explores solutions to the Subset Sum problem: given a set of numbers and a target sum, find a subset of those numbers that adds up exactly to the target.

* **Hill-Climbing:** A local search algorithm. The "neighbor" states are defined by either adding one new element to the current subset or removing one element from it.
* **Genetic Algorithm (GA):** A population-based optimization algorithm. This implementation includes:
    * **Population Initialization:** Creating an initial set of random solutions (subsets).
    * **Crossover:** A single-point crossover function to combine two parent solutions.
    * **Mutation:** A mutation function to introduce random changes and maintain diversity.
    * **Evolution:** The population evolves over several generations to find a solution that minimizes the difference from the `target_sum`.
* **Naive Search (Brute Force):** A complete search algorithm that checks every possible subset to find the exact, optimal solution. This is used as a baseline to verify the results of the heuristic methods.

---

## Usage

This project is structured as a (likely) Jupyter Notebook. The helper functions for graph generation and plotting are provided. The core task was to complete the algorithm implementations marked with `TODO`.

To run this project:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/[YOUR_REPOSITORY].git
    cd [YOUR_REPOSITORY]
    ```

2.  **Install dependencies (if any):**
    ```bash
    # It's recommended to use a virtual environment
    # pip install numpy matplotlib
    ```

3.  **Run the Notebook:**
    Open the `.ipynb` file in Jupyter Notebook, Jupyter Lab, or Google Colab and run the cells sequentially.

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* (Likely) **Matplotlib** & **NumPy** for graph plotting and numerical operations.

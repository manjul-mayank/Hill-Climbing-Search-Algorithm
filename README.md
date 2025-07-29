-------------------------------------------------------------------------------------------------------
----------------------- Question----------------------
-------------------------------------------------------------------------------------------------------
A local search algorithm tries to find the optimal solution by exploring the states in
the local region. Hill climbing is a local search technique that constantly looks for a
better solution in its neighborhood.
1. Implement the Hill Climbing Search Algorithm for solving the 8-puzzle
2. problem.
Check the algorithm for the following heuristics:
a. h1(n) = number of tiles displaced from their destined position.
b. h2(n) = sum of the Manhattan distance of each tile from the goal
position.

# 🌄 Hill Climbing Algorithm – AI Search Technique

This repository contains an implementation of the **Hill Climbing algorithm** for solving optimization problems using a local search strategy. This project was developed as part of an AI course assignment focused on heuristic search methods.

---

## 🧠 What is Hill Climbing?

Hill Climbing is a heuristic search algorithm that starts with an arbitrary solution and iteratively makes small changes to improve it. If a change produces a better solution, the algorithm continues from that new point.

This algorithm is commonly used in:
- Pathfinding
- Constraint satisfaction
- Optimization problems

---

## 📂 Files Included

- **`Hill_Climb_ new code.ipynb`**  
  Jupyter Notebook containing the full implementation, problem setup, and visual output of the algorithm.

- **`.gitignore`**  
  To ignore system-generated and virtual environment files.

- **`LICENSE`**  
  MIT License allowing free use, modification, and distribution.

---

## ▶️ How to Run

1. Open the notebook using Jupyter:
   ```bash
   jupyter notebook "Hill_Climb_search.ipynb"

Run cells sequentially to:

Generate the problem space

Apply hill climbing

Visualize the search behavior

✅ Features
Customizable problem graph/state space

Modular implementation of the algorithm

Clearly structured and commented code for educational use

🔍 Sample Use Cases
Solving simple optimization problems

Demonstrating local maxima/minima

Educational purposes in AI search courses

🧑‍💻 Author
Manjul Mayank
Artificial Intelligence
Hill Climbing Algorithm

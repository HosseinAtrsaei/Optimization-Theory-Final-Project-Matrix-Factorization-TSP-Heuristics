# Optimization-Theory-Final-Project-Matrix-Factorization-TSP-Heuristics
This repository contains the final project for the **Introduction to Optimization** course at **Télécom Paris**. The project is divided into two parts, each showcasing the application of optimization techniques to classical problems in machine learning and operations research.

## 📌 Project Overview

### 1. Matrix Factorization for Recommendation Systems

We solve a **low-rank matrix factorization** problem for a user-item rating matrix (MovieLens 100k dataset), using:

- **Block-Coordinate Descent (BCD)** optimization
- Closed-form updates for user and item vectors
- Regularization to prevent overfitting
- Analysis of:
  - Strong convexity of subproblems
  - Convergence of BCD
  - Computational complexity per iteration

The goal is to approximate missing ratings and learn user preferences & item characteristics.

---

### 2. Traveling Salesman Problem (TSP)

We implement and compare heuristic algorithms for solving the classic **TSP**, using instances from the [TSPLIB](http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/tsp/):

- **Simulated Annealing**
  - Tested with 3 types of neighbor selection
- **Genetic Algorithm**
  - Compared crossover and mutation strategies
- **Ant Colony Optimization**
  - Tested various pheromone parameters and algorithm variants

We compare the three approaches in terms of:
- **Solution accuracy**
- **Runtime performance**
- **Scalability on small and large datasets**

---

# Optimization Problem: Exhaustive Enumeration vs. Genetic Algorithm

## Introduction
This repository explores different approaches to solving an integer optimization problem with a nonlinear constraint. The problem involves project selection under budgetary, project count, and management capacity constraints.

## Problem Statement
The objective is to maximize the total return from selected projects without exceeding the available budget, maximum number of projects, and a nonlinear management capacity constraint.

### Given Data:
- **Maximum Budget (B):** 50 million reais.
- **Number of Projects (n):** 20.
- **Maximum Projects Selection (K):** 5.
- **Project Costs (c):** [5,10,7,8,6,9,12,15,20,17,3,11,14,18,4,16,19,13,2,1] million reais.
- **Expected Returns (r):** [10,15,9,14,11,13,20,25,30,28,8,17,22,26,12,24,27,19,7,5] million reais.
- **Management Capacity (C):** 16.

## Solution Approaches

### 1. Exhaustive Enumeration
The exhaustive enumeration method evaluates all possible project combinations to find the optimal solution. While this approach guarantees an optimal solution, it becomes computationally expensive as the number of projects increases.

#### Limitations:
- Computational complexity increases exponentially.
- Impractical for large-scale problems.

### 2. Genetic Algorithm (GA)
The Genetic Algorithm (GA) offers an efficient heuristic approach to solving the optimization problem. GA simulates the process of natural selection by using operations such as selection, crossover, and mutation to iteratively improve solutions.

#### Advantages of GA:
- **Efficiency:** Provides near-optimal solutions in a reasonable time.
- **Scalability:** Handles larger problem instances better than exhaustive search.
- **Flexibility:** Adaptable to various constraints and objective functions.


## Conclusion
While exhaustive enumeration guarantees an optimal solution, it is impractical for larger problems. The Genetic Algorithm, on the other hand, provides a practical and scalable approach to finding near-optimal solutions efficiently.



---

# Algorithm-Optimisation 🚁♻️

### Drone-Based Pollution Cleanup Optimisation Project
#### COT4400: Analysis of Algorithms — Spring 2025 (University of South Florida)

---

## 📌 Project Overview

This project explores **different algorithmic strategies** (Dynamic Programming, Brute Force, and Greedy) applied to the **Drone-Based Pollution Cleanup Problem**, developed as part of the **Analysis of Algorithms (COT4400)** course at USF.

The goal is to **maximize environmental impact** by optimizing how an AI-powered drone selects and cleans pollution hotspots under strict battery and travel constraints.

This repository contains two Jupyter Notebooks, each implementing and analyzing alternative algorithmic approaches to the problem.

---

## 🌍 Problem Description

An environmental agency deploys a drone to clean **pollution hotspots** in a region.

### Hotspot Characteristics:

* **Priority Score**: Environmental importance of the hotspot (higher = more critical).
* **Cleaning Effort**: Energy required to fully clean the hotspot.
* **Distance from Dock**: Round-trip energy cost for travel.

### Drone Specifications (per mission):

* **Battery Capacity**: 1000 energy units.
* **Cleaning Efficiency**: 1 energy unit = 1 unit of pollution cleaned.
* **Travel Rules**:

  * Must return to dock after each hotspot visit.
  * Energy use = *travel + cleaning*.
  * Partial cleaning is allowed (priority earned proportionally).

### Objective:

> **Maximize the total priority score** across all visited hotspots in one mission, subject to battery constraints.

---

## 🧮 Algorithmic Approaches

The notebooks demonstrate multiple optimization strategies:

1. **Brute Force** 🔎

   * Explores all possible combinations of hotspots.
   * Guarantees optimal solution but is computationally expensive (exponential time).

2. **Greedy** ⚡

   * Prioritizes hotspots based on heuristic rules (e.g., highest priority-to-energy ratio).
   * Runs much faster, but may not always yield optimal solutions.

3. **Dynamic Programming (DP)** 📊

   * Uses memory-efficient state representation (similar to Knapsack optimization).
   * Achieves optimal or near-optimal performance with polynomial complexity.

Each notebook includes:

* Problem formulation
* Algorithm implementation
* Complexity analysis
* Performance testing with plots and comparisons

---

## 📂 Repository Structure

```
Algorithm-Optimisation/
│
├── notebooks/
│   ├── BruteForce_Greedy_Approach.ipynb   # Implements and analyzes brute force + greedy
│   ├── DynamicProgramming_Approach.ipynb  # Implements and analyzes DP solution
│
└── README.md   # Project documentation
```


---

## 📊 Results

* **Brute Force** finds exact maximum but slows down drastically as hotspots grow.
* **Greedy** provides quick but sometimes suboptimal solutions.
* **Dynamic Programming** balances efficiency and accuracy, scaling well.

Graphs in the notebooks illustrate **execution time vs. solution quality** for each method.

---

## 🎯 Learning Outcomes

Through this project, the following skills were reinforced:

* Analyzing complex computational problems
* Applying **algorithmic strategies** (Brute Force, Greedy, Dynamic Programming)
* Evaluating **time/space complexity**
* Implementing and testing algorithms in **Python/Jupyter**
* Visualizing performance trade-offs

---

## 📚 References

* COT4400: Analysis of Algorithms, University of South Florida, Spring 2025

---

## 👨‍💻 Author

**Joshua Maharaj**
Spring 2025 — Individual Project for **COT4400: Analysis of Algorithms**

---


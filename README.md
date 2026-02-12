# CSCN8020 - Reinforcement Learning Programming  
## Assignment 1 (Value Iteration + Monte Carlo)

This repository contains my solutions for **CSCN8020 Assignment 1**, based on topics from Reinforcement Learning, Markov Decision Processes (MDPs), Value Iteration, and Off-policy Monte Carlo methods.

---

## 📌 Assignment Overview

This assignment focuses on solving reinforcement learning problems using both **model-based** and **sample-based** approaches.

The following problems are included:

### **Problem 1: Pick-and-Place Robot as an MDP**
- Designed the robot control problem as an MDP
- Defined states, actions, rewards, and explained reasoning
- Focused on smooth and fast robotic movement

### **Problem 2: 2×2 Gridworld Value Iteration**
- Performed two iterations of Value Iteration manually
- Used Bellman Optimality Equation
- Computed the updated values step-by-step

### **Problem 3: 5×5 Gridworld Value Iteration**
- Implemented reward function:
  - Goal state reward = +10
  - Grey states reward = -5
  - Normal states reward = -1
- Implemented:
  - Standard Value Iteration
  - In-place Value Iteration
- Extracted:
  - Optimal value function (V*)
  - Optimal policy (π*)
- Compared performance and computational complexity

### **Problem 4: Off-policy Monte Carlo with Importance Sampling**
- Implemented Off-policy Monte Carlo Control using Weighted Importance Sampling
- Used:
  - Behavior policy = random policy
  - Target policy = greedy policy
- Estimated value function V(s)
- Compared Monte Carlo results with Value Iteration results

---

## 🛠️ Technologies Used
- Python 3.x
- NumPy
- Jupyter Notebook

---

## 📂 Files Included

- `Assignment.ipynb` → Final notebook solution for all problems


## ▶️ How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt

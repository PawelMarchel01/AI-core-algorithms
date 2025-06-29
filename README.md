# 🤖 AI Core Algorithms

This repository is dedicated to implementing core Artificial Intelligence algorithms from scratch. It is designed for educational purposes and experimentation with various AI-based approaches to optimization and search problems.

---

## 🧠 Algorithm Overview

### 1. **TSP – Traveling Salesman Problem**

A collection of different AI approaches to solving the classic TSP:

- 🔍 **DFS / BFS**: Brute-force traversal of the graph to find valid paths.
- 📊 **NN / KNN**: Nearest Neighbor and K-Nearest Neighbor heuristics.
- 🌟 **A\***: Pathfinding with both admissible and non-admissible heuristics.
- 🐜 **Ant Colony Optimization**: A bio-inspired algorithm modeling the behavior of ants to find optimal paths.

All methods are implemented manually for a better understanding of each approach, with performance comparisons.

---

### 2. **Genetic Algorithm – Work Scheduling**

A Genetic Algorithm (GA) is used to generate optimal or near-optimal work schedules.

- Each individual encodes a possible schedule.
- Operators: Selection, Crossover, and Mutation.
- Fitness is based on meeting constraints and minimizing schedule conflicts.
- 🟩 Final output includes **Gantt chart visualizations** (screenshots provided).
  ![Gantt Chart](00.Images/GAN.jpg)
  
---

### 3. **Particle Swarm Optimization – Function Minimization**

Particle Swarm Optimization (PSO) is applied to find the minimum of a mathematical function `f(x, y)`.

- Particles move through the search space influenced by:
  - Their own best known position
  - The global best known position
- ✨ The optimization process is visualized using an animated **GIF** showing particle movement over iterations.

  ![Particle Swarm Optimization](00.Images/PSO.gif)
  
---

### 4. **Fuzzy Logic – Tip Prediction & SVM**

Applications of fuzzy logic in regression and classification tasks:

- 🍽️ **Fuzzy TSK Model**:  
  A 0-order Takagi-Sugeno-Kang inference system that predicts tip amounts (0–15%) based on food and service quality (0–10).  
  Uses triangular/trapezoidal membership functions and fuzzy rules.

- 🧪 **SVM vs Fuzzy SVM**:  
  Comparison of standard SVM with its fuzzy variant, which is more robust to noisy data.  
  Evaluated on synthetic datasets with linear, polynomial, and RBF kernels.

---

### 5. **Logic Gates – Differentiable & Evolutionary Models**

Exploring logic-based neural architectures for classification and network discovery:

- 🔗 **Differentiable Logic Gates (DLG)**:  
  A custom neural network trained on the **MONK dataset**, using differentiable logic gates instead of standard activations.  
  Highlights the interpretability of logic-inspired decision boundaries in gradient-based learning.

- 🧬 **Logic Gate Neural Network + GA (LGNN)**:  
  A neural network made entirely of logic gates (AND, OR, XOR, NOT), evolved via a **Genetic Algorithm** to match a target network.  
  Demonstrates how GAs can reverse-engineer logical structures from behavior alone.

---

## 👨‍💻 Author

**Paweł Marchel**  
If you find this project helpful, feel free to star ⭐ the repo or get in touch for collaboration.

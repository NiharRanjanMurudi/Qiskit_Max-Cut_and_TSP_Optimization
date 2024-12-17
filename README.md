# Qiskit Max-Cut and TSP Optimization

## Description

This repository demonstrates the implementation of **Max-Cut** and **Traveling Salesman Problem (TSP)** using the **Qiskit framework**. It explores and compares classical and quantum approaches to solve combinatorial optimization problems, highlighting their applications and performance.

## Problems Addressed

1. **Max-Cut Problem**  
   - Objective: Partition a graph's vertices into two subsets such that the total weight of edges between the subsets is maximized.  
   - Applications:
     - Circuit Design
     - Chemical Design
     - Social Network Analysis  

2. **Traveling Salesman Problem (TSP)**  
   - Objective: Find the shortest route that visits all cities exactly once and returns to the starting city.  
   - Applications:
     - Logistics Optimization
     - Quantum Circuit Optimization
     - Traffic Flow Management  

## Methods Used

1. **Classical Approach**  
   - Brute-force methods to provide exact results for small problem instances.

2. **Quantum Approach**  
   - Problems are reformulated into **Ising Hamiltonians**.
   - Solved using:
     - **Variational Quantum Eigensolver (VQE)**
     - **Quantum Approximate Optimization Algorithm (QAOA)**  

## Tools & Libraries

- **Qiskit**: Quantum computing framework  
- **NetworkX**: Graph generation and manipulation  
- **Matplotlib**: Visualization of graphs and solutions  
- **NumPy**: Numerical computations  

## Repository Contents

- **max_cut_and_tsp.ipynb**:  
  Jupyter Notebook with the implementation of Max-Cut and TSP using Qiskit.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/NiharRanjanMurudi/Qiskit_Max-Cut_and_TSP_Optimization.git
   cd Qiskit_Max-Cut_and_TSP_Optimization
   ```

2. **Install dependencies**:
   ```bash
   pip install qiskit matplotlib networkx numpy
   ```

3. **Run the notebook**:  
   Open and execute the Jupyter Notebook:
   ```bash
   jupyter notebook max_cut_and_tsp.ipynb
   ```

## Results

1. **Max-Cut Problem**:
   - Successfully partitioned graph nodes into two subsets, maximizing edge weights.

2. **Traveling Salesman Problem**:
   - Found the shortest route for given graphs using classical and quantum solvers.

## Key Insights

- Classical methods (brute force) are effective for small instances but lack scalability.
- Quantum approaches, leveraging VQE and QAOA, offer better scalability for larger graphs by exploring multiple solutions simultaneously.

## Conclusion

This project showcases the power of **quantum computing** for solving combinatorial optimization problems like Max-Cut and TSP. Using Qiskit, we demonstrate how quantum algorithms can outperform classical methods for larger problem instances.

# Variational Quantum Algorithms (VQA) Exploration ⚛️💻

[![Jupyter Notebook](https://img.shields.io/badge/Made_with-Jupyter-F37626.svg?logo=Jupyter)](https://jupyter.org/)
[![Quantum Computing](https://img.shields.io/badge/Quantum-Computing-blueviolet)](#)

Welcome to the **Variational Quantum Algorithm** repository! This project is a comprehensive collection of Jupyter Notebooks dedicated to exploring, implementing, and analyzing various Variational Quantum Algorithms (VQAs). 

VQAs are hybrid quantum-classical algorithms that are currently the most promising path toward achieving quantum advantage on Noisy Intermediate-Scale Quantum (NISQ) devices.

## 📋 Table of Contents

- [Overview](#-overview)
- [Repository Structure](#-repository-structure)
  - [1. Core Algorithms](#1-core-algorithms)
  - [2. Ansatz Design & Analysis](#2-ansatz-design--analysis)
  - [3. Advanced VQE Methods](#3-advanced-vqe-methods)
  - [4. Linear Algebra & Optimization](#4-linear-algebra--optimization)
  - [5. Error Correction & Open Systems](#5-error-correction--open-systems)
- [Prerequisites & Installation](#-prerequisites--installation)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔬 Overview

This repository explores the mathematical foundations and code implementations of various VQAs, ranging from standard Variational Quantum Eigensolvers (VQE) and Quantum Approximate Optimization Algorithms (QAOA) to advanced subspace expansion methods, ansatz expressibility, and open system simulations.

---

## 🗂️ Repository Structure

The notebooks in this repository are categorized into the following core topics:

### 1. Core Algorithms
Fundamental implementations of the most widely used hybrid quantum-classical algorithms.
* 📓 `Variational_quantum_eigensolver.ipynb` - Standard implementation of VQE to find the ground state energy of a Hamiltonian.
* 📓 `qaoa.ipynb` - Quantum Approximate Optimization Algorithm for solving combinatorial optimization problems.

### 2. Ansatz Design & Analysis
Exploration of different parameterized quantum circuits (Ansätze) and their properties.
* 📓 `Variational_ansatz.ipynb` - Introduction to building parameterized quantum circuits.
* 📓 `Hybrid_ansatz.ipynb` - Designing hybrid ansätze tailored for specific hardware/problem constraints.
* 📓 `Unitary_coupled_clustered_ansatz.ipynb` - UCCSD ansatz implementation, widely used in quantum chemistry.
* 📓 `Ansatz_expressibility.ipynb` - Measuring the expressibility and entangling capability of different quantum circuits.
* 📓 `Ansatz_for_mixed_states.ipynb` - Adapting variational circuits to represent and prepare mixed quantum states.

### 3. Advanced VQE Methods
Techniques to improve the convergence, accuracy, and efficiency of standard VQE.
* 📓 `Adiabatically_assissted_vqe.ipynb` - Combining adiabatic state preparation with VQE for better initial state guesses.
* 📓 `Subspace_vqe.ipynb` / `Subspace_approach.ipynb` - Utilizing subspace methods to find excited states and mitigate errors.
* 📓 `Subspace_expansion_method.ipynb` - Quantum Subspace Expansion (QSE) for error mitigation and excited state calculations.
* 📓 `Iterative_approach.ipynb` - Iterative variations of VQA for dynamic problem-solving.

### 4. Linear Algebra & Optimization
Using quantum algorithms to solve classical linear algebra problems.
* 📓 `Linear_equation_solver.ipynb` - Variational Quantum Linear Solver (VQLS) approaches.
* 📓 `Matrix_vector_multiplication.ipynb` - Quantum implementations of matrix-vector multiplications.
* 📓 `Orthogonality_constrained_vqc.ipynb` - Variational Quantum Classifiers (VQC) with orthogonality constraints.
* 📓 `Cost calculation using expectation value.ipynb` - Efficient strategies for Hamiltonian averaging and cost function evaluation.

### 5. Error Correction & Open Systems
Dealing with noise, decoherence, and real-world quantum system modeling.
* 📓 `Quantum_error_correction.ipynb` - Basics of QEC codes and integrating them with variational approaches.
* 📓 `simulating_open_system.ipynb` - Simulating quantum systems interacting with an environment (Lindblad master equations).

---

## ⚙️ Prerequisites & Installation

To run these notebooks locally, you will need Python 3.8+ and standard quantum computing libraries (like Qiskit or Pennylane, depending on the specific notebook implementation).

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/JayAmeta11/Variational_Quantum_Algorithm.git](https://github.com/JayAmeta11/Variational_Quantum_Algorithm.git)
   cd Variational_Quantum_Algorithm

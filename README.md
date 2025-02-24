# Quantum Programming Labs

This repository contains a collection of Jupyter notebooks covering various notes of my quantum programming lab classes using Qiskit. The notebooks are designed to provide both a theoretical overview and implementation examples.

## Course Structure

### Fundamentals
A comprehensive introduction to quantum computing basics and Qiskit implementation (like quantum gates, state manipulation, and multi-qubit systems)
- [**quantum_programming_labs/fundamentals/fundamentals.ipynb**](fundamentals/basic_circuits.ipynb)
- [**quantum_programming_labs/fundamentals/sampler_and_estimators.ipynb**](fundamentals/sampler_and_estimators.ipynb)

### Quantum Algorithms
Implementation and analysis of key quantum algorithms:

#### Variational Quantum Eigensolver (VQE)
Introduction to hybrid quantum-classical algorithms with focus on finding ground state energies of molecules.
- [**quantum_programming_labs/algorithms/VQE.ipynb**](algorithms/VQE.ipynb)

#### Quantum Approximate Optimization Algorithm (QAOA)
Implementation of QAOA for solving combinatorial optimization problems, demonstrated through MaxCut examples.
- [**quantum_programming_labs/algorithms/QAOA.ipynb**](algorithms/QAOA.ipynb)

#### Quantum Machine Learning (QML)
Exploration of quantum-enhanced machine learning techniques, focusing on quantum kernels and QSVM implementation.
- [**quantum_programming_labs/algorithms/qml_implementation.ipynb**](algorithms/qml_implementation.ipynb)

### Quantum Systems
Advanced quantum computing concepts:

#### Error Correction
Introduction to quantum error correction techniques and their implementation.
- [**quantum_programming_labs/quantum_systems/error_correction.ipynb**](quantum_systems/error_correction.ipynb)

#### Quantum Communication
Exploration of quantum communication protocols and quantum key distribution.
- [**quantum_programming_labs/quantum_systems/quantum_communication.ipynb**](quantum_systems/quantum_communication.ipynb)

## Requirements
- Python 3.8+
- Qiskit
- Additional requirements can be found in `requirements.txt` (for VQE and QSVVM are qiskit-ibm-runtime == 0.21 required!)

## Usage
Each notebook is self-contained and includes:
- Theoretical background
- Code implementation
- Examples and exercises
- Visualizations of results

Clone the repository and open the notebooks in Jupyter to get started:
```bash
git clone https://github.com/yourusername/quantum_programming_labs.git
cd quantum_programming_labs
jupyter notebook
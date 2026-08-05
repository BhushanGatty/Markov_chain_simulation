This repository contains a Jupyter Notebook that explores the fundamental concepts and computational methods of Markov Chains using Python.

<img width="1244" height="869" alt="0" src="https://github.com/user-attachments/assets/e4b4e1c6-fedc-4525-80eb-aabe03a4c4e5" />


## Project Overview

Markov Chains are mathematical systems that experience transitions from one state to another according to certain probabilistic rules. This notebook demonstrates how to analyze a simple Markov Chain through various approaches:

1.  **Random Walk Simulation:** Simulating state transitions over a fixed number of steps to visualize the chain's behavior.
2.  **Monte Carlo Simulation:** Approximating the stationary distribution of the Markov Chain by simulating a large number of transitions and observing the frequency of each state.
3.  **Repeated Matrix Multiplication:** Calculating the powers of the transition matrix `A^n` to show how the system converges to its stationary distribution over time.
4.  **Left Eigenvector Analysis:** Determining the exact stationary distribution by finding the left eigenvector corresponding to an eigenvalue of 1 for the transition matrix.

## Example

The notebook uses a simple 3-state system (Burger, Pizza, Hotdog) to illustrate these concepts, where `A` is the transition matrix defining the probabilities of moving between states.

## Technologies Used

*   Python
*   `numpy` for numerical operations and matrix calculations
*   `scipy.linalg` for eigenvalue decomposition



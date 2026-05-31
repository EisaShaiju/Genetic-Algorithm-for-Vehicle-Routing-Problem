# Genetic Algorithm for Vehicle Routing Problem (VRP)

This project implements a Genetic Algorithm (GA) to solve a multi-vehicle routing problem using the DEAP framework in Python. 

## Features
* **Multi-Objective Optimization:** Evaluates fitness by minimizing both the total travel distance and the workload imbalance (standard deviation) between the vehicle routes.
* **Evolutionary Operators:** Utilizes Partially Matched Crossover (PMX), shuffle index mutation, and tournament selection for efficient permutation-based optimization.
* **Visualization:** Automatically plots the optimal depot-to-location routes for all vehicles using Matplotlib.

## Dependencies
Requires Python 3.x and the following libraries:
* `deap`
* `numpy`
* `matplotlib`

## Usage
Run the script directly. It will initialize a population of 300, evolve it over 300 generations, output statistical metrics for each generation, and render a 2D plot of the best-found route configuration.
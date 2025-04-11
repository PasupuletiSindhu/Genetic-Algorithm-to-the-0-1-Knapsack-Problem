# Genetic-Algorithm-to-the-0-1-Knapsack-Problem

This Jupyter Notebook implements a simplified version of a Genetic Algorithm (GA), focusing exclusively on the **selection** mechanism. It appears to be part of an assignment or project, specifically **Question 2** in a problem set.

## Description

This notebook applies a **Genetic Algorithm** to the **0/1 Knapsack Problem**, focusing solely on the **selection** phase of the evolutionary process. The GA does not involve crossover or mutation, allowing an analysis of how selection mechanisms influence the optimization process on their own.

- **Population Initialization**: Random binary vectors represent item selections.
- **Fitness Function**: Evaluates how well each individual satisfies the knapsack constraints while maximizing value.
- **Selection Methods**: Supports different strategies like:
  - **Roulette Wheel Selection (RWS)**: Probability-based selection proportional to fitness.
  - **Tournament Selection (TS)**: Selects the best from a random subset of individuals.
- **GA Loop**: For a given number of generations, the algorithm:
  - Computes fitness for all individuals.
  - Selects pairs based on a selection criterion.
  - Updates the population with the selected individuals.

The algorithm tracks the best fitness, average fitness, and activity over generations, optionally visualizing the evolution of the solution.

## Features

- Simulates a Genetic Algorithm without crossover or mutation.
- Focuses on how selection alone affects the evolution of the population.
- Includes several iterations of GA steps, tracking fitness and population dynamics.

## Structure

- Initialization of population
- Fitness evaluation
- Selection strategies (roulette wheel, tournament)
- Analysis and visualization of population performance over generations

## Usage

To run this notebook:

1. Open the notebook using Jupyter Lab or Jupyter Notebook.
2. Execute cells sequentially.
3. Review inline visualizations and output.

## Requirements

Make sure you have the following Python libraries installed:

```bash
pip install numpy matplotlib pandas

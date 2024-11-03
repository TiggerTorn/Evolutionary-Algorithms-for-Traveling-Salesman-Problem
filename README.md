# Evolutionary-Algorithms-for-Traveling-Salesman-Problem

This project investigates the application of Evolutionary Algorithms (EAs) to solve the Traveling Salesman Problem (TSP), an optimization challenge where the objective is to find the shortest route that visits a set of cities exactly once and returns to the starting point. The implementation is developed using Python and evaluates the performance of various EA configurations on datasets representing city maps from Brazil and Burma.

## The Evolutionary Algorithm
The Evolutionary Algorithm (EA) for solving the Traveling Salesman Problem (TSP) in this project begins with generating an initial population of random solutions and assessing their fitness based on the total travel cost derived from a distance matrix. The algorithm proceeds as follows:

- **Generate Population**: Create an initial set of random solutions.
- **Tournament Selection**: Select parents for crossover.
- **Single-Point Crossover**: Produce offspring by combining parent solutions.
- **Swap Mutation**: Introduce variation by swapping genes in the offspring.
- **Fitness Check**: Evaluate if the new solution is better.
- **Replacement**: Incorporate the fittest offspring into the population, replacing existing members.
- **Iteration**: Repeat the process for 10,000 fitness evaluations or until the termination criterion is met to evolve towards the optimal TSP route.

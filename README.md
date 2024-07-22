# genetic-algorithm-without-library
This project implements a Genetic Algorithm (GA) from scratch to solve optimization problems without relying on any external libraries.

***Project Description***

This project is the final assignment for the Artificial Intelligence course. The goal is to implements a Genetic Algorithm (GA) from scratch to solve optimization problems without relying on any external libraries. The GA is used to find the optimal solution for a mathematical function using a population of potential solutions. The algorithm includes key components such as initialization, selection, crossover, mutation, and replacement.

***Features***
- Initialization: Generates an initial population of binary chromosomes.
- Fitness Calculation: Evaluates the fitness of chromosomes based on a custom mathematical function.
- Selection: Uses tournament selection to choose parents for the next generation.
- Crossover: Applies single-point crossover to produce offspring from parents.
- Mutation: Mutates chromosomes with a specified probability to maintain diversity.
- Survivor Selection: Selects the best individuals to form the next generation.

***Table of Contents***
- Usage
- Algorithm Details
	- Initialization
	- Fitness Function
	- Selection
	- Crossover
	- Mutation
	- Survivor Selection
- Results

***Usage***
1. Save the provided code into a file
2. Run the code

***Algorithm Details***
1. Initialization
The algorithm starts by initializing a population of binary chromosomes. Each chromosome represents potential solutions in the search space.
2. Fitness Function
The fitness of each chromosome is evaluated using a mathematical function. The goal is to minimize this function, so fitness is defined as the reciprocal of the function value.
3. Selection
Tournament selection is used to choose parents for the next generation. A subset of individuals is randomly selected, and the best individuals within this subset are chosen as parents.
4. Crossover
Single-point crossover is applied to create offspring from two parent chromosomes. A crossover point is randomly chosen, and the genetic material is exchanged between parents.
5. Mutation
Mutation is performed on offspring with a specified probability to introduce genetic diversity. Each bit in the chromosome has a chance of being flipped.
6. Survivor Selection
The new generation of chromosomes is formed by selecting the best individuals from the combined population of parents and offspring.

***Results***

The script prints the fitness value of the best chromosome found, along with the corresponding values of x1 and x2. The results show the best solution found after running the genetic algorithm for the specified number of generations.

# Travelling-Salesman-Problem-using-Genetic-Algorithm
_Travelling Salesman Problem Using Genetic Algorithm_.


A solution to the travelling salesman problem requires we set up a genetic algorithm in a specialized way. For instance, a valid solution would need to represent a route where every location is included at least once and only once. If a route contain a single location more than once, or missed a location out completely it wouldn't be valid and we would be valuable computation time calculating it's distance.

## Travelling Salesman Problem

Travelling Salesman Problem is a situation in which a salesman is allowed to travel n number of cities, with the following conditions-

    1. Salesman has to visit each city only once.
    2. Salesman has to finish at the city he has started.

The possible paths between any 2 cities is (N-1).

![TSP](https://github.com/Ratna04priya/Travelling-Salesman-Problem-using-Genetic-Algorithm/blob/master/tsp.png)

## Genetic Algorithm

Genetic Algorithm works as search heuristic.

It is used as an excellent method of solving some very interesting AI problems. They work on the motive of Survival of the Fittest. In genetic algorithm, combinational expansion is handled.

The basic operations in genetic algorithm includes -

    1. Selection : Selects the best entries of the population.
    2. Crossover : Recombines the entries to produce next generation.
    3. Mutation : Adds randomness to the reproduction process.
![GA](https://github.com/Ratna04priya/Travelling-Salesman-Problem-using-Genetic-Algorithm/blob/master/ga.png)


## About the Project

In this project, the 7 cities are taken and approx distance between them. Using the python libraries the various possiblities and selections of path are printed.

Using Genetic Algorithm, an optimal solution is shown which satisfies the conditions of Travelling Salesman Problem.


# Genetic-algorithms-for-portfolio
Genetic algorithms for portfolio
The target's of work
Read the data.
Calculate the historical returns for 3 months, 6 months, 12 months, 24 months and 36 months for each of the stocks.
Define Gene : A fraction of the total capital assigned to a stock.
Define Chromosome : Set of genes i.e. fractions of total capital assigned to each stock. Sum of each chromosome should be equal to 1.
Generate Initial Population : A set of randomly generated chromosomes.
Fitness function (Function). Sharpe ratio.
Select Elite Population (Function): It filters the elite chromosomes which have highest returns, which was calculated in fitness function.

Mutation: A function that will perform mutation in a chromosome. Randomly we shall choose 2 numbers between 0, 5 and those elements we shall swap.

Crossover: Heuristic crossover or Blend Crossover uses the ﬁtness values of two parent chromosomes to ascertain the direction of the search. It moves from worst parent to best parent.

Next Generation (Function): A function which does mutation,mating or crossover and builds a new generation of chromosomes.

Iterate the process: Iterate the whole process till their is no change in maximum returns or for fixed number of iterations.

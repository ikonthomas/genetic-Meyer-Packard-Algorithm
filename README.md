# genetic-Meyer-Packard-Algorithm
Predicting a Stock Price Using a Genetic Algorithm

The genetic algorithm is a method for solving both constrained and unconstrained optimization problems that is based on natural selection, the process that drives biological evolution. The genetic algorithm repeatedly modifies a population of individual solutions. At each step, the genetic algorithm selects individuals at random from the current population to be parents and uses them to produce the children for the next generation. Over successive generations, the population "evolves" toward an optimal solution.The genetic algorithm uses three main types of rules at each step to create the next generation from the current population: •	Selection rules select the individuals, called parents, that contribute to the population at the next generation. •	Crossover rules combine two parents to form children for the next generation. •	Mutation rules apply random changes to individual parents to form children.


1.	 past data as input as a set of {x , y} where x would be a multidimensional vector containing data like general market movement etc. and y a price representation
2.	create an initial population of conditions C
3.	evaluate each C based on past data (when C is true, what are the values for y) with a probability density function
4.	apply crossover to the set of C’s. In this process two C elements with a high fitness value( i.e. evaluation) are picked and their data combined similar to the creation of new DNA from to strings of parent DNA
5.	apply mutation. Randomly change certain C’s so that conditions not featured in the initial population can be created.
6.	Go to step 3 and repeat until model converges, i. e. C’s do not significantly change anymore.

# Graph-Coloring
A code which effectively colors a given graph


Approach used : Genetic algorithm, greedy algorithm


Description of approach used:

Firstly, the program starts from getting greedy solution. In greedy algorithm, it colors the first node. Then moves to other node and checks adjacency by use of adjacency matrix and also whether it has already colored or not checking "arr" array.The result is the maximum color numbers. Then as in TSP, this inital solution is added to the mating pool,calculated its fitness value. Other individuals of mating pool have been obtained by bitwise mutation of greedy solution. The fitness value of each individual has been calculated and compared with respect to optimal value. The next steps are crossover and bitwise mutation for getting new chromosomes.The aim of genetic algorithm is to make better the previous greedy solution.


All relevant parameters and their settings:

Population Size = 200
Maximum Iteration = 200
Tournament Size = 20
Crossover Probability = 0.8
Mutation Probability = 0.5


NOTE: Take one of the data files which is located in the same directory here and add it to code's argument.

References:
[1] Kosaraju’s algorithms to find SCC in DAG
https://github.com/chenyukang/CodeSnippet/blob/master/geeksforgeeks/strongly-connected-components.cc

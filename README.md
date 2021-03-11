## Computing nearest neighbour interchange distances between ranked phylogenetic trees

Lena Collienne and Alex Gavryushkin


## Abstract

Many popular algorithms for searching the space of leaf-labelled (phylogenetic) trees are based on tree rearrangement operations.
Under any such operation, the problem is reduced to searching a graph where vertices are trees and (undirected) edges are given by pairs of trees connected by one rearrangement operation (sometimes called a move).
Most popular are the classical nearest neighbour interchange, subtree prune and regraft, and tree bisection and reconnection moves.
The problem of computing distances, however, is **NP**-hard in each of these graphs, making tree inference and comparison algorithms challenging to design in practice.

Although ranked phylogenetic trees are one of the central objects of interest in applications such as cancer research, immunology, and epidemiology, the computational complexity of the shortest path problem for these trees remained unsolved for decades.
In this paper, we settle this problem for the ranked nearest neighbour interchange operation by establishing that the complexity depends on the weight difference between the two types of tree rearrangements (rank moves and edge moves), and varies from quadratic, which is the lowest possible complexity for this problem, to **NP**-hard, which is the highest.
In particular, our result provides the first example of a phylogenetic tree rearrangement operation for which shortest paths, and hence the distance, can be computed efficiently.
Specifically, our algorithm scales to trees with tens of thousands of leaves (and likely hundreds of thousands if implemented efficiently).

[*Journal of Mathematical Biology,* 82, 8, 2021](https://doi.org/10.1007/s00285-021-01567-5)

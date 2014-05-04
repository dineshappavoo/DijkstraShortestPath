Dijkstra's Shortest Path 
=======================

Dijkstra's Shortest Path algorithm implementation in java.

Dijkstra's algorithm  is a graph search algorithm that solves the single-source shortest path problem
for a graph with non-negative edge path costs, producing a shortest path tree. This algorithm is often 
used in routing and as a subroutine in other graph algorithms.

##Complexity
	  Worst case performance  O(|E| + |V| |log|V|)
	  Worst case space complexity O (|V|)

##Functionality

This library has the implementation of Dijkstra's algorithm to find the shortest path in a directed graph G=[V,E].The 
following code snippet shows how to get the shortest path,

    DijkstraAlgorithm dijkstraAlgorithm = new DijkstraAlgorithm();
	dijkstraAlgorithm.findShortestPath();

###Input
	3 3
	1 2 1
	2 3 2
	1 3 3

First integer is the total number of vertices |V| in the graph G. The next integer is the number of edges |E| in the graph.
Next |E| lines has the edges information (u, v, w). All inputs must be given through terminal.

###Output
	 Distance for 1 is 0
	 Distance for 2 is 1
	 Distance for 3 is 3
  
##Project Contributor

* Dinesh Appavoo ([@DineshAppavoo](https://twitter.com/DineshAppavoo))

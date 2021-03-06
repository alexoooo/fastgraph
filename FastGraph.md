#summary Graph algorithm with fast node merging.

= Introduction =

An undirected, weighted graph data structure more efficient than adjacency maps is presented.
Merging of graph nodes is heavily optimized without sacrificing the performance of other operations.
Cluster analysis is shown to benefit significantly.

= Details =

Graphs consist of nodes joined by edges.
Nodes have data, and edges have weights.
There are a many operations that make a graph, their performance varies with implementation.
Many problems can be expressed in terms of graphs, among them is cluster analysis.
In cluster analysis items are grouped by similarity.
The graph implementation presented here is shown to work well for cluster analysis.
This code is my final project for DePaul CSC503. It is a simple parallel implementation of Kruskal's algorithm.

This code was tested and developed on Ubuntu 10.10 in Python 2.7.

The PSim.py class is needed to run parallel_kruskal.py.

In order to run parallel_kruskal.py, you must enter 5 command line arguments in order:
1 - number of nodes to create with PSim
2 - number of vertices in the graph
3 - number of edges in the graph
4 - option to use heuristic (1 for yes, 0 for no)
5 - run serial version instead, ignores param 1 (1 for yes, 0 for no)

Example to run 5 nodes, with 10 vertices, and 100 edges using the heuristic option:
python parallel_kruskal.py 5 10 100 1 0
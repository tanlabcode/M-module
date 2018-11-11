# M-module

The M-module algorithm is designed for identifying gene modules with common members but varied connectivity across multiple gene networks. We term these resulting modules M-modules. It takes as inputs multiple edge-weighted gene networks and a set of prior probabilities representing the importance of a gene for the conditions under study. Along with network topological features, the prior probabilities are used to rank and select seeds to initialize module search. We transform the M-module search problem into a minimum entropy problem by introducing a graph-entropy-based objective function for M-modules. Finding M-modules whose entropy values are all minimal is an NP-hard problem. We therefore developed a greedy algorithm for M-module search based on seed expansion. Empirical p-values of candidate M-modules are determined by using randomized networks. For more details of the algorithm, users are referred to the original publication on the algorithm 1. The Cytoscape plugin version of the algorithm provides module search function as well as additional functions for analyzing and visualizing the dynamics of M-modules across multiple networks. The package also contains a command line version of the software for advanced users.

# Software Installation 
After downloading the software package, place the M-module.jar file in the plugins sub-directory under the Cytoscape directory. M-module can be launched by selecting it from the plugins drop-down menu. 

# Running M-module
See User_Manual.docx for details.

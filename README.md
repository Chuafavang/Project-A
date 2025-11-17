1. Function to create intial W matrix.
We only focus on Barabási–Albert (BA) Networks and Watts–Strogatz (WS) Networks
For Watts–Strogatz (WS) Networks, we have:
n - number of agents
d - number of nearest nodes ( must be even number)
p - probability of rewiring

For Barabási–Albert (BA) Networks, we have:
n - number of agents
m - initial existing agents

How to input the argument ( Refer to the testing file)
Function W = create_initial_W_matrix(n, d, p, m, seed, network)
network ='BA' for Barabási–Albert networks
network ='WS' for Watts–Strogatz networks

Note: if d is not needed for Barabási–Albert networks, set d=[]

2. Function to plot the network
For simplicity, we only plot undirected graph.
The node size is corresponding to its number of neighbours

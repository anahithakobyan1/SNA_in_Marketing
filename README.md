# SNA_in_Marketing

This project utilizes Social Network Analysis (SNA) techniques to design a targeted marketing campaign for a hypothetical telecom company. 

## Methodology
We use a dataset (connections.txt) representing the company's customer network, where each node represents a customer and each edge represents a connection between two customers. The data is analyzed using Python and NetworkX, a powerful library for the study of the structure and dynamics of complex networks.

First we load the data and create a graph object in NetworkX.

Then we apply the Louvain algorithm to detect communities in the network. These communities are groups of nodes that are densely connected internally.

We calculate degree, closeness, betweenness and eigenvector centralities for each node in the graph. These centrality measures help us identify the most influential nodes in the network.

We identify key influencers in each community based on their centrality measures.

And finally we do visualizations, plot the overall network and the identified communities, highlighting the influencers.

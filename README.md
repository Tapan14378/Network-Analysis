# Network-Analysis

The provided code focuses on network analysis using Python libraries such as pandas, matplotlib.pyplot, seaborn, and networkx. Here is a summary of the code's functionality and how it works:

1. Importing Libraries: The required libraries for network analysis are imported, including pandas, numpy, networkx, matplotlib.pyplot, seaborn, and warnings. Matplotlib settings are also adjusted for visualizations.

2. Data Understanding: The code reads an input file ("social-network.csv") containing edge data for a social network. It processes the edges, converts them into a list of tuples (sorted in ascending order), and creates a graph object using the NetworkX library. The code then prints the number of edges and nodes in the graph.

3. Statistical Analysis: The code performs statistical analysis on the social network graph, focusing on degree centrality, clustering coefficient, and assortativity.

- Degree Centrality: The code creates a Counter object to count the frequency of each degree in the graph. It then prints highly connected nodes with degrees greater than 100 and plots the degree distribution using a scatterplot.

- Clustering Coefficient: The code calculates the average clustering coefficient of the network using the nx.clustering function from NetworkX. It also creates a pandas dataframe with the clustering coefficients and plots a histogram of the coefficients.

- Assortativity: The code calculates the assortativity coefficient of the network using the nx.degree_assortativity_coefficient function. It prints the assortativity coefficient, which indicates the tendency of nodes in the network to link with similar nodes based on their degree or qualities.

4. Visualization: The code visualizes the network graph by selecting leaf nodes (nodes with a degree of one) and removing a portion of them from the graph. It then uses the nx.draw function from NetworkX to draw the modified graph.

The code provides insights into the network's structure and characteristics, such as node degrees, clustering coefficient, assortativity, and graph visualization.

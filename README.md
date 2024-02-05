# citation-network

A citation network is a representation of relationships between academic or research papers based on their citations. In scholarly work, when one paper cites another, it establishes a connection between them. A citation network, therefore, is a graph where each node represents a paper, and directed edges between nodes indicate the direction of citation (i.e., which paper is citing another).

These networks are used in bibliometrics and scientometrics to analyze the flow of information, identify influential papers or authors, and understand the structure of the academic literature within a specific field. The structure of a citation network can reveal patterns of influence, key research topics, and the interconnectedness of scholarly work.

## Terminology

- **Source Publication (Source):** EPA funded research chosen for scraping citations.
- **Target:** Citations used in the source publication.

## Graphs

In mathematics, graph theory studies graphs, mathematical structures used to model pairwise relations between objects. A graph consists of vertices (nodes/points) connected by edges (links/lines). Graphs can be undirected (symmetric edges) or directed (asymmetric edges).

**Question for Consideration:**
- If the graph is Hamiltonian complete, what does it imply for our bibliometric network? (Hamiltonian cycle checker algorithm exists for Python.)

## Key Network Analysis Concepts

Understanding network analysis involves various concepts:

- **Nodes and Edges:** Basic components of networks.
- **Clusters:** Groups of related nodes.
- **Degree:** Number of connections a node has.
- **Betweenness Centrality:** How influential a node is.
- **Modularity:** Community structure.

[Learn more in this Gephi Tutorial](https://www.youtube.com/watch?v=gcfAT8aMxuQ)

## Network Visualization and Analysis with Gephi

For a deeper dive, explore this resource from Nodus Labs: [Network Visualization and Analysis with Gephi](https://noduslabs.com/courses/gephi/)

## Centrality Measures

- **Centrality:** A general term for how close a node is to the network.
- **Degree Centrality:** Number of links connected to a node.
- **Closeness Centrality:** Average length of the shortest path between the node and all other nodes.
- **Betweenness Centrality:** Based on the number of times a node is crossed by each of the least cost paths.

## Clustering

- **Clustering Coefficient:** Compares the number of connections to other nodes in a group.

A clustering coefficient of 1 indicates a complete group or clique ([Learn more](https://en.wikipedia.org/wiki/Clustering_coefficient)).

## Research Database

Found a research database at [EPA Research Database :: Environmental Protection Agency Ireland](https://www.epa.ie/publications/research/), though it's less useful than [https://www.epa.ie/publications/research/](https://www.epa.ie/publications/research/).

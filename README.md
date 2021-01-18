# GitHub Social Network Analysis

*Angelina Khatiwada, MSc Data Science and Economics, UNIMI*

Dec, 2020

**Network description**:

A large social network of GitHub developers which was collected from the public API in June 2019. Nodes are developers who have starred at least 10 repositories and edges are mutual follower relationships between them. 

Properties (from project website):

- Undirected graph
- Node features: Yes.
- Edge features: No.
- Node labels: Yes. Binary-labeled.
- Nodes: 37,700
- Edges: 289,003
- Density: 0.001
- Transitvity: 0.013


Source: https://snap.stanford.edu/data/github-social.html


**Analysis**:
- Dataset import and preprocessing
- Degree Analysis
- ECDF and ECCDF
- Comparison with an Erdos-Renyi random graph G(N, p)
- Hubs and isolated nodes detection
- Transitivity and local clustering coefficient
- Centrality
- Assortativity
- Community detection

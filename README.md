# GitHub Social Network Analysis

*Angelina Khatiwada, MSc Data Science and Economics, UNIMI*

Dec, 2020

### Network description: ###

A large social network of GitHub developers which was collected from the public API in June 2019. Nodes are developers who have starred at least 10 repositories and edges are mutual follower relationships between them. Github user is either a web or a machine learning developer (binary classification: 0 and 1). This target feature was derived from the job title of each user.

Properties (from project website):
- Undirected graph
- Node labels: Yes. Binary-labeled
- Nodes: 37,700
- Edges: 289,003

Source: https://snap.stanford.edu/data/github-social.html


### Analysis includes: ###
- Dataset import and preprocessing
- Degree Analysis
- ECDF and ECCDF
- Comparison with an Erdos-Renyi random graph G(N, p)
- Hubs and isolated nodes detection
- Transitivity and local clustering coefficient
- Centrality
- Assortativity
- Community detection

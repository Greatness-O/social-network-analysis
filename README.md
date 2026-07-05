# Facebook Social Network Analysis

A network science analysis of the [SNAP ego-Facebook dataset](https://snap.stanford.edu/data/ego-Facebook.html), exploring network structure, edge centrality and community detection.

## Overview

1. **Builds the network** from `facebook_combined.txt` (4,039 users, ~88k friendship edges) and reports basic characteristics: node/edge counts, density, average degree.
2. **Estimates edge betweenness centrality** (sampled approximation) and plots its distribution to identify bridge edges connecting different parts of the network.
3. **Detects communities** using two algorithms and compares them: Greedy Modularity Maximisation and Label Propagation.

## Results

| Metric | Value |
|---|---|
| Nodes | 4,039 |
| Edges | 88,234 |
| Density | 0.0108 |
| Average degree | 43.7 |
| Louvain communities | 16 (modularity 0.8349) |
| Label Propagation communities | 44 (modularity 0.7368) |

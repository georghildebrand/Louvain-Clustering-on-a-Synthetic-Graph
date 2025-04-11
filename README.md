# Louvain-Clustering-on-a-Synthetic-Graph

# Louvain Community Detection on Synthetic Graphs

Using Louvain is relevant in the context of Graph RAG. This notebook is a demo of the concept. It demonstrates how the Louvain algorithm can automatically infer the number of communities (clusters) in a graph based on modularity optimization.

It does the following steps:

- Generates a synthetic graph with planted community structure using NetworkX.
- Applies the **Louvain community detection algorithm** (via `python-louvain` package).
- Automatically determines the number of communities.
- Visualizes the graph with nodes colored by community.

## 📦 Dependencies

```bash
pip install networkx matplotlib python-louvain
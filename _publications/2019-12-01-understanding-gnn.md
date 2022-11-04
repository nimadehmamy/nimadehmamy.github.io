---
title: "Understanding the representation power of graph neural networks in learning graph topology"
collection: publications
permalink: /publication/2015-10-01-understanding-gnn
excerpt: 'We analyze the expressive power of graph neural networks (GNN).'
date: 2019-12-1
venue: 'NeurIPS 2019'
paperurl: 'https://proceedings.neurips.cc/paper/2019/file/73bf6c41e241e28b89d0fb9e0c82f9ce-Paper.pdf'
citation: 'Dehmamy, N., Barabási, A. L., & Yu, R. (2019). &quot;Understanding the representation power of graph neural networks in learning graph topology&quot;. <i>Advances in Neural Information Processing Systems</i>, 32.'
---

We show that GNN, specifically graph convolutional networks (GCN), can learn graph features, such as degree of nodes, and higher order graph moments (polynomial functions of the adjacency matrix $A$) with $O(1)$ number of parameters. 
We also show that the node propagation (aggregation) rule can play an important role in the ability of GNN to learn moments. 
For example, using $f(A) = D^{-1/2}AD^{-1/2}$ ($D$ being the diaginal degree matrix), a shallow GCN fails to learn the degrees of nodes, whereas a GCN with $f(A)=A$ can easily learn the degrees. 
Assuming that ML tasks on graphs would benefit from learning graph moments, we show that combining multiple propagation rules in each layer and using skip connections can significantly imrpove expressivity of GCN. We further analyze the abaility of GCN-based GNN to classify graph topologies (e.g. random Erdős–Rényi graphs vs. scale-free Barabasi-Albert model).
We find that depth is often more important than width for such tasks.  


[NeurIPS 2019](https://proceedings.neurips.cc/paper/2019/file/73bf6c41e241e28b89d0fb9e0c82f9ce-Paper.pdf)
[arXiv](https://arxiv.org/abs/1907.05008)

Dehmamy, N., Barabási, A. L., & Yu, R. (2019). "Understanding the representation power of graph neural networks in learning graph topology". <i>Advances in Neural Information Processing Systems</i>, 32.

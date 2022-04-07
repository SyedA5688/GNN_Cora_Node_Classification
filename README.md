# GNN_Cora_Node_Classification
Node classification project on the Cora citation dataset, developed for CS 4337 Data Science II.


This repository contains code developed by Syed Rizvi for a node classification project for CS 4337, Spring 2022.
This project explored different GNN layers for a node classification task on the Cora citation network
dataset. The goal was not necessarily to achieve peak performance (all models trained to somewhere around 80% node 
classification accuracy on Cora), but rather to contrast the different properties of the different GNN layers as 
well as their implementation details.



## Interesting implementation differences between these layers: 
1. GraphSAGE neighbor sampling approach, implemented using Pytorch Geometric NeighborSampler
2. Attention coefficients obtained from Graph Attention layer



## Main Packages and Libraries:
1. Pytorch
2. Pytorch Geometric



## The GNN layers implemented are:
1. Graph Convolutional layer
2. GraphSAGE layer
3. Graph Attention layer



## References:
1. Kipf, Thomas N., and Max Welling. "Semi-supervised classification with graph convolutional networks." arXiv preprint arXiv:1609.02907 (2016).
2. Hamilton, Will, Zhitao Ying, and Jure Leskovec. "Inductive representation learning on large graphs." Advances in neural information processing systems 30 (2017).
3. Veličković, Petar, et al. "Graph attention networks." arXiv preprint arXiv:1710.10903 (2017).
4. Fey, Matthias, and Jan Eric Lenssen. "Fast graph representation learning with PyTorch Geometric." arXiv preprint arXiv:1903.02428 (2019).



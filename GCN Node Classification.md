# GCN Node Classification on Cora

## Overview
This project trains a Graph Convolutional Network (GCN) on the Cora citation dataset using PyTorch Geometric.  
The model performs node classification by learning from the graph structure and node feature vectors.

## What the Code Does
- Loads the Cora dataset (graph, features, labels).
- Builds a two-layer GCN model.
- Trains the model using the labeled subset of nodes.
- Evaluates the model on the test set to measure classification accuracy.

## Improvements Made
The following changes increased accuracy from about 60% to over 80%:

- Increased the hidden layer size to improve feature representation.
- Added dropout to reduce overfitting.
- Added weight decay (L2 regularization) for better generalization.
- Trained for more epochs to allow the model to converge properly.

## Result
After applying these improvements, the model achieves approximately 80–82% test accuracy on the Cora dataset instead of 62% before the improvement.

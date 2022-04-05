## Implementation of a custom message passing layer for GNN (Graph Neural Networks)

This Colab notebook is the deliverable of task 1 containing the implementation and evaluation of the Message Passing layer (See CustomMPLayer). It is implemented as an instance of torch_geometric.nn.conv.MessagePassing, making it easily pluggable and compatible with Torch Geometric framework. Acknowldgement: The working of this layer is evaluated using PyTorch Lightning module, the skeleton/base code of which is obtained from the UvA DL tutorials: https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial7/GNN_overview.html and modified for appropriate use. Evaluation is done on the CORA dataset.

### Usage: 
Simply run all the cells on Google Colab. The performance of the model (Training, Validation, and Testing accuracy) using the implementation of this custom Message Passing layer on CORA dataset will be calculated and displayed. The hyperparameters can be chosen as needed.

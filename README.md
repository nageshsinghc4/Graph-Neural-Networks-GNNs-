# Graph-Neural-Networks-GNNs

we will implement a type of graph neural network (GNN) known as _ message passing neural network_ (MPNN) to predict graph properties. Specifically, we will implement an MPNN to predict a molecular property known as blood-brain barrier permeability (BBBP).

Motivation: as molecules are naturally represented as an undirected graph G = (V, E), where V is a set or vertices (nodes; atoms) and E a set of edges (bonds), GNNs (such as MPNN) are proving to be a useful method for predicting molecular properties.

Until now, more traditional methods, such as random forests, support vector machines, etc., have been commonly used to predict molecular properties. In contrast to GNNs, these traditional approaches often operate on precomputed molecular features such as molecular weight, polarity, charge, number of carbon atoms, etc. Although these molecular features prove to be good predictors for various molecular properties, it is hypothesized that operating on these more "raw", "low-level", features could prove even better.


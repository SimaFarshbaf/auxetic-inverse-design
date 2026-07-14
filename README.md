# auxetic-inverse-design
An inverse design framework of energy-absorbing graded auxetic metamaterials via layer-wise decomposition and deep learning


This repository provides the implementation of a physics-guided machine learning framework for the efficient design and analysis of thickness-graded auxetic lattice metamaterials. The project introduces a layer-wise decomposition strategy that reconstructs the global mechanical response of graded auxetic structures from independent single-layer simulations, reducing the computational cost of nonlinear finite element analysis from more than 10,000 full-structure simulations to only 11 single-layer analyses.

The generated dataset is used to train both forward and inverse deep neural networks (DNNs) for predicting energy absorption and identifying optimal thickness distributions. In addition, a Physics-Guided Neural Network (PGNN) incorporates a physics-based thickness–energy relationship into the training process, enabling improved extrapolation, higher accuracy, and significantly reduced training data requirements compared to conventional DNNs.

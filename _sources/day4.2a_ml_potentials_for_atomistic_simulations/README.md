## ML potentials for atomistic simulations

The course materials below were used during one of the Specialization Topic sessions of the AI School and provide an introduction to *machine learning interatomic potentials* (MLIPs), aimed at students and researchers interested in combining atomistic simulations with machine learning techniques.

We explored a hands-on toy example, demonstrating how both *neural networks* (NNs) and *Gaussian process regression* (GPR) can be used to learn a simple potential energy surface from data.

We introduced *graph neural networks* (GNNs) and their advantages for learning interatomic interactions in complex systems, and we applied these concepts in a "real-world" example, where participants trained GNN-based interatomic potentials for a material system and used the trained model to perform molecular dynamics simulations.

The course materials, including Jupyter notebooks and example data, are available [here](https://github.com/omidshy/ml-notebooks.git).

The materials were covered in the following order:

1. `gaussian-process-regression.ipynb`
2. `MB-potential-gaussian-process-regression.ipynb`
3. `MB-potential-neural-network.ipynb`
4. `graph-pes-water.ipynb`

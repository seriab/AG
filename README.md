# Notebooks de ejemplos

Esta carpeta contiene Jupyter notebooks de diferentes pruebas de AG.


## One-Max

A continuación se enumeran los ejemplos:

- **[Algoritmo Genetico - OneMax](01Algoritmo_Genetico_OneMax.ipynb):** Este código ha sido escrito a mano, sin utilizar ningún framewor).
- **[Algoritmo Genetico - OneMax con Deap](02Algoritmo_Genetico_OneMax_Deap.ipynb):** demonstrates how you can solve the brax task "humanoid" using PGPE, with GPU support, if available.
  
## Problema de la Mochila
  
- **[Minimizing Lennard-Jones Atom Cluster Potentials](03Problema_de_la_mochila_real.ipynb):** recreates experiments from [the paper introducing `SNES`](https://dl.acm.org/doi/abs/10.1145/2001576.2001692), showing that the algorithm can effectively solve the challenging task of [minimising Lennard-Jones atom cluster potentials](https://pubs.acs.org/doi/abs/10.1021/jp970984n).
- **[Training MNIST30K](04Problema_de_la_mochila_con_nsga2_Deap.ipynb):** recreates experiments [from a recent paper](https://www.deepmind.com/publications/non-differentiable-supervised-learning-with-evolution-strategies-and-hybrid-methods) which demonstrates that `SNES` can be used to solve supervised learning problems. The script in particular recreates the training of the 30K-parameter 'MNIST30K' model on the MNIST dataset, but can easily be reconfigured to recreate other experiments from that paper.
- **[Variational Quantum Eigensolvers with SNES](05Problema_de_la_mochila_con_nsga2_Platypus.ipynb):** re-implements (with some minor changes in experimental setup), [experiments in a recent paper](https://iopscience.iop.org/article/10.1088/2632-2153/abf3ac) demonstrating that `SNES` is a scalable alternative to [analytic gradients on a quantum computer](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.99.032331), and can practically optimize [Quantum Eigensolvers](https://www.nature.com/articles/ncomms5213).
- **[Genetic Programming](06Problema_de_la_mochila_con_nsga2_Inspyred.ipynb):** demonstrates genetic programming with GPU support.

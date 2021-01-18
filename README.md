# Ising model on Tensorflow
The notebook can simulate Ising model on a chain/square/cube/N-d hypercubic lattice.
The Ising model consists of +/-1 at each lattice site.
A clean model at a finite temperature can be simulated using Metropolis-Hashtings algorithm.
The update can be parallelized using a checkerboard lattice, since it has nearest-neighbor interactions only.
As a result, it can be simulated on a GPU very efficiently.
Tensorflow library is used to demonstrate this on a square lattice Ising model with uniform Ferromagnetic interaction and a uniform field at a non-zero temperature.

# Requirement
- tensorflow 2.x
- numpy
- matplotlib
- ipywidgets

# Try in Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sayanbasak0/ising-tensorflow/main?filepath=Ising_tensorflow_v2.ipynb)

# Try in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/github/sayanbasak0/ising-tensorflow/blob/main/Ising_tensorflow_v2.ipynb)

# Disclaimer


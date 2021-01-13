# Ising model on Tensorflow
The notebook can simulate Ising model on a chain/square/cube/N-d hypercubic lattice.
The Ising model consists of +/-1 at each lattice site.
A clean model at a finite temperature can be simulated using Metropolis-Hashting algorithm.
The update can be parallelized using a checkerboard lattice, since it has nearest-neighbor interactions only.
As a result, it can be simulated on a GPU very efficiently.
Tensorflow library is used to demonstrate this on a square lattice Ising model with uniform Ferromagnetic interaction and a uniform field at a non-zero temperature.

# Requirement
- tensorflow 1.x
- numpy
- matplotlib

# Disclaimer
Use at your own risk!

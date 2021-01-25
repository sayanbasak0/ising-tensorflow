[![Launch Binder](https://raw.githubusercontent.com/sayanbasak0/ising-tensorflow/heroku/icons/binder_badge_logo.svg?v_DATE)](https://mybinder.org/v2/gh/sayanbasak0/ising-tensorflow/heroku?filepath=Ising_tensorflow_v2.ipynb)
[![Open in Colab](https://raw.githubusercontent.com/sayanbasak0/ising-tensorflow/heroku/icons/colab-badge.svg?v_DATE)](https://colab.research.google.com/github/sayanbasak0/ising-tensorflow/blob/heroku/Ising_tensorflow_v2.ipynb)
[![Run Heroku App](https://raw.githubusercontent.com/sayanbasak0/ising-tensorflow/heroku/icons/heroku-logo-solid-gradient.svg?v_DATE)](https://ising-using.herokuapp.com/)

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


# Disclaimer


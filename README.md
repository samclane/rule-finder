# Rule Finder

An attempt to use neural networks to reverse-engineer the rules of a cellular automaton.

## Experiments


### 1. ca.ipynb

A 1-dimensional, 7-neighbor (r=3) cellular automaton, inspired from [this page](https://cellpylib.org/neighbourhood.html) in the cellpylib documentation. Could overfit the network, but never got any good validation results.

### 2. nks.ipynb

Tried to go back to basics with the [Elementary cellular automata](https://cellpylib.org/eca.html) from New Kind of Science (NKS). Network accuracy never went above 0.57, and the network coudn't ever validate on the test set.
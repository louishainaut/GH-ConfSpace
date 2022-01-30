# Configuration spaces on a wedge of spheres

This repository contains the code related to the article "Configuration spaces on a wedge of spheres and higher Hochschild homology" by Nir Gadish and Louis Hainaut

## Abstract


## Code

The files in this repository allow to do the following computations:
- SymGroup + GL decomposition: Computes lower bounds for the cohomology groups and provides helper functions to improve the readability of the results. Up to n=10 the code offers the possibility to correct the lower bounds in order to obtain the exact answer. For a higher number of particles it only corrects the multiplicity of the symmetric and exterior powers.
- Ranks-GL-Irrep-Multidim & Ranks-GL-Irrep-Equidim: Compute the multiplicities of representations of the general linear group. The second algorithm is more intuitive in the sense that it gives immediately the (integral) multiplicity of the GL-representation investigated, but it is much less efficient. The first algorithm is more efficient; in order to make its use more intuitive the function 'Multiplicity' tells us which linear combination of the coefficients we are computing the rank of. By varying the inputs and comparing the linear combinations it is possible to isolate the contribution of any single Schur functor.  
- traces for gl: Implements the Fox-Neuwirth algorithm for computing the multiplicities of S_n representations. One can also use this code to compute the trace of certain diagonal endomorphisms of the free group. This file has a large overlap with the code used in [arXiv: 2109.03302](https://arxiv.org/abs/2109.03302)

## Data presentation

See this webpage.

# FastLomap

FastLomap has modified the Lomap algorithm to handle perturbation maps for hundreds of free energy perturbation calculations.

While Lomap checks each edge individually to satisfy constraints, FastLomap introduces a chunk check process to check whether multiple edges can be removed simultaneously.

FastLomap is tens to hundreds of times faster, and the generated graph is equivalent to that of Lomap.

## Prerequisites

* RDKit Release > 2021
* NetworkX
* Matplotlib
* python > 3.8

Authors
-------

See [AUTHORS.md](https://github.com/ohuelab/FastLomap/blob/main/AUTHORS.md)

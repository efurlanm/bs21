# Comparison of High-performance Computing Approaches in the Python Environment for a Five-point Stencil Test Problem

The test problem is a known problem of heat transfer over a finite surface, modeled by the partial differential equation of Poisson. It models the normalized temperature distribution on a surface over a series of iterations that make up the simulation. As commonly used for numerical solutions, this equation is discretized in a finite grid and solved using a finite difference method. The specific algorithm requires the calculation of a 5-point stencil in the 2D domain grid to update temperatures every step of the time.

The different implementations are in the Jupyter Notebook files in this repository. Notebooks were also used for experimentation, and a better organization, as well as better documentation, is a work in permanent construction. Some parts of Notebooks use the Portuguese language. As a tip, it is possible to use the Python environment and the Jupyter Notebook / JupyterLab to analyze the results and generate graphs. Also, the file extension ".ipynb" is a text file format that can be opened by Python as a text file to be analyzed.


# Acknowledgements

Authors thank LNCC (National Laboratory for Scientific Computing) for grant 205341 AMPEMI (call 2020-I), which allows access to the Santos Dumont supercomputer (node of the SINAPAD, the Brazilian HPC system).


# License

The main work follows the CC0 license. Other authors included or mentioned follow their respective licenses.
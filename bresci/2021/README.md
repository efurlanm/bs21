# Comparison of High-performance Computing Approaches in the Python Environment for a Five-point Stencil Test Problem

Several of the most important high-performance computing approaches available in the Python programming environment of the LNCC Santos Dumont supercomputer, are compared using a specific test case. Python includes specific libraries, development tools, implementations, documentation, optimization and parallelization resources. It provides a straightforward way to program using a high level of abstraction, but the parallelization features for exploring multiple cores, processors or accelerators, such as GPUs, are diverse and may not be easily chosen by the user. Fortran 90 serial and parallel implementations of the test case are taken as benchmarks to compare performance. This work is a primer for the use of HPC resources in the Python.

The adopted test problem is a known problem of heat transfer over a finite surface, modeled by the partial differential equation of Poisson. It models the normalized temperature distribution on a surface over a series of iterations that make up the simulation. As commonly used for numerical solutions, this equation is discretized in a finite grid and solved using a finite difference method. The specific algorithm requires the calculation of a 5-point stencil in the 2D domain grid to update temperatures every step of the time.

The different implementations are in the Jupyter Notebook files in this repository. Notebooks were also used for experimentation, and an organization of ideas was attempted, but it is still a work in progress.



# Acknowledgements

Authors thank LNCC (Laboratório Nacional de Computação Científica) for grant 205341 AMPEMI (call 2020-I), which allows access to the Santos Dumont supercomputer (node of the SINAPAD, the Brazilian HPC system).
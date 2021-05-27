# Comparison of High-performance Computing Approaches in the Python Environment for a Five-point Stencil Test Problem

The test problem is a known problem of heat transfer over a finite surface, modeled by the partial differential equation of Poisson. It models the normalized temperature distribution on a surface over a series of iterations that make up the simulation. As commonly used for numerical solutions, this equation is discretized in a finite grid and solved using a finite difference method. The specific algorithm requires the calculation of a 5-point stencil in the 2D domain grid to update temperatures every step of the time.

The different implementations are in the Jupyter Notebook files in this repository. Notebooks were also used for experimentation, and a better organization, as well as better documentation, is a work in permanent construction. Some parts of Notebooks use the Portuguese language.


# Acknowledgements

Authors thank LNCC (National Laboratory for Scientific Computing) for grant 205341 AMPEMI (call 2020-I), which allows access to the Santos Dumont supercomputer (node of the SINAPAD, the Brazilian HPC system).


# Links of interest

* BALAJI, P. et al. Advanced MPI Programming. Tutorial at SC17, November 2017. Original code that was adapted and used in this work. https://www.mcs.anl.gov/~thakur/sc17-mpi-tutorial/
* CARMO, B. S. et al. USP CADASE Project. Tutorial on using SDumont, including using the Jupyter Notebook (in Portuguese). https://sites.usp.br/cadase/recursos-computacionais/tutoriais-sdumont/
* SDumont official website (in Portuguese). https://sdumont.lncc.br/
* Using Jupyter Notebooks on Bridges. Pittsburgh Supercomputing Center. https://www.psc.edu/resources/software/jupyter/
* Using Jupyter Notebook. Mississippi Center for Supercomputing Research. https://mcsr.olemiss.edu/docs/using-jupyter-notebook/
* How do I get started with Jupyter Notebooks? Minnesota Supercomputing Institute. https://www.msi.umn.edu/support/faq/how-do-i-get-started-jupyter-notebooks


# License

The main work follows the CC0 license. Other authors included or mentioned follow their respective licenses. 
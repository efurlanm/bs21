# Comparison of HPC approaches in the Python environment for a 5-point stencil test problem

This work is a small primer for the use of HPC resources in the Python programming environment, including Jupyter Notebook, in particular the use on a supercomputer. The test problem is a known problem of heat transfer over a finite surface, modeled by the partial differential equation of Poisson. It models the normalized temperature distribution on a surface over a series of iterations that make up the simulation. As commonly used for numerical solutions, this equation is discretized in a finite grid and solved using a finite difference method. The specific algorithm requires the calculation of a 5-point stencil in the 2D domain grid to update temperatures every step of the time.

This repository contains only the implementation codes, which are in the Jupyter Notebook (JN) files. The JN were also used for experimentation, and improvements, organization, documentation, and translation from Portuguese to English, is a work in permanent construction.


## Related work

Milligan [[1]](#1) describes how the Minnesota Supercomputing Institute at the University of Minnesota adopted support for interactive HPC computing and user-friendly reproducible computing using Jupyter Notebook (JN), in a supercomputing environment that includes scheduling and job control. JN is not restricted to the Python language, it can be used for other languages. Feedback surveys showed that students prefer the JN platform more than the traditional command line on the console.

Thomas et al. [[2]](#2) describes the use of JN, a popular and flexible web application for literate computing, for interactive and data intensive supercomputing in a Cray XC40 Cori system, at the National Center for Scientific Computing in Energy Research (NERSC). The work shows motivation, implementation, and lessons learned.

Mansour et al. [[3]](#3) describes


## Acknowledgements

Authors thank LNCC (National Laboratory for Scientific Computing) for grant 205341 AMPEMI (call 2020-I), which allows access to the Santos Dumont supercomputer (node of the SINAPAD, the Brazilian HPC system).


## References mentioned in this document

<div id="1">[1] Milligan, M. (2017). Interactive hpc gateways with jupyter and jupyterhub. In Proceedings of the Practice and Experience in Advanced Research Computing 2017 on Sustainability, Success and Impact (pp. 1-4). </div>
<div id="2">[2] Thomas, R., Canon, S., Cholia, S., Gerhardt, L., & Racah, E. (2017, May). Toward interactive supercomputing at NERSC with Jupyter. In Cray User Group (CUG) Conference Proceedings. Cray User Group (CUG). </div>
<div id="2">[3] Mansour, J., Giordani, J., Moresi, L., Beucher, R., Kaluza, O., Velic, M., ... & Beall, A. (2020). Underworld2: Python geodynamics modelling for desktop, hpc and cloud. </div>


## Links of interest

* BALAJI, P.; et al. Advanced MPI Programming. Tutorial at SC17, November 2017. Original code that was adapted and used in this work. https://www.mcs.anl.gov/~thakur/sc17-mpi-tutorial/
* CARMO, B. S.; et al. USP CADASE Project. Tutorial on using SDumont, including using the Jupyter Notebook (in Portuguese). https://sites.usp.br/cadase/recursos-computacionais/tutoriais-sdumont/
* SDumont official website (in Portuguese). https://sdumont.lncc.br/
* Using Jupyter Notebooks on Bridges. Pittsburgh Supercomputing Center. https://www.psc.edu/resources/software/jupyter/
* Using Jupyter Notebook. Mississippi Center for Supercomputing Research. https://mcsr.olemiss.edu/docs/using-jupyter-notebook/
* How do I get started with Jupyter Notebooks? Minnesota Supercomputing Institute. https://www.msi.umn.edu/support/faq/how-do-i-get-started-jupyter-notebooks
* Python prototyping, Jupyter, Celery, Ipyparallel-Scikit-learn, and Scoop-Deap. Aion Supercomputer. Université du Luxembourg. https://ulhpc-tutorials.readthedocs.io


## License

The main work follows the CC0 license. Other authors included or mentioned follow their respective licenses. 
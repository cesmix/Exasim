# exasim

# Partial Differential Equation Application Builder For Extreme Scalable Simulations
Exasim is an open-source software for generating discontinuous Galerkin codes and building executable applications to numerically solve  parametrized partial differential equations (PDEs) on different computing platforms with distributed memory.  It combines high-level languages  and low-level languages to easily create parametrized PDE models and automatically produce high-performance applications. The construction of {\em parametrized} PDE models and the generation of the stand-alone C++ production code are handled by high-level languages, while the production code itself can run on various machines, from laptops to the largest supercomputers, with both CPU and GPU processors. 

# Dependency  

Exasim automatically generates and compiles stand-alone C++ code on the fly. To do that, Exasim requires a C++ compiler and Blas/Lapack libraries for building serial applications. An MPI library is required to build parallel applications. CUDA Tookit is required to build applications on Nvidia GPUs. Gmesh is used for mesh generation. METIS is needed for mesh partitioning. And Paraview is used for visualization. Please see the documentation for installation of these required packages.



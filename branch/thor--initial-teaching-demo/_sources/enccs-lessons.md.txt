```{instructor-note}
   - 10 min teaching
   - 5 min discussion
``` 

# ENCCS Lessons

Below is a list of current ENCCS lessons along with their intended learning outcomes. 
These lessons are at different maturity levels and have been developed by many different people, 
so they do not all conform equally well to the recommendations presented in this lesson!


## GPU computing

**[OpenMP for GPU Offloading](https://enccs.github.io/openmp-gpu/miniapp/)**

- Get an overview of the architecture of GPU and how they differ from CPUs
- Understand how OpenMP fits into the landscape of GPU programming approaches
- Understand OpenMP's shared parallel model and program execution model
- Learn how to use basic OpenMP directives and clauses

**[OpenACC](https://enccs.github.io/OpenACC/)**

- Get an overview of the architecture of GPU and how they differ from CPUs
- Understand how OpenACC fits into the landscape of GPU programming approaches
- Understand OpenACC's shared parallel model and program execution model
- Learn how to use basic OpenACC directives and clauses

**[Intermediate CUDA](https://enccs.github.io/CUDA/)**

- Get an overview of the architecture of GPU and how they differ from CPUs
- Understand GPU concepts like threads, blocks and streaming multiprocessors 
- Learn to write simple CUDA kernels
- Learn to work with GPU memory
- Learn to optimize CUDA kernels
- Understand asynchronous execution

**[SYCL](https://enccs.github.io/sycl-workshop/)**

- What is SYCL and why it is useful.
- Write hardware-agnostic code to express parallelism using the queue, command group, and kernel abstractions.
- Use buffer and accessors to handle memory across devices.
- Evaluate drawbacks and advantages of unified shared memory.
- Get acquainted with the SYCL profiling API.

**[GPU Programming: Why, When and How=](https://enccs.github.io/gpu-programming/)**

- Understand why and when to use GPUs.
- Become comfortable with key concepts in GPU programming.
- Acquire a comprehensive overview of different software frameworks, what levels they operate at, and which to use when.
- Learn the fundamentals in at least one framework to a level which will enable you to quickly become a productive GPU programmer.


## HPC

**[Intermediate MPI](https://enccs.github.io/intermediate-mpi/)**

- Understand communicators, groups and derived datatypes
- Learn to use one-sided communication
- Understand and be able to use collective communication, blocking and non-blocking
- Understand how to work with MPI and threads

## Programming languages

**[High-performance Data Analytics with Python](https://enccs.github.io/hpda-python/)**

- Have a good overview of available tools and libraries for improving performance in Python
- Know what libraries are available for efficiently storing, reading and writing large data
- Be comfortable working with NumPy arrays and Pandas dataframes
- Be able to explain why Python code is often slow
- Understand the concept of vectorisation
- Understand the importance of measuring performance and profiling code before optimising
- Be able to describe the difference between "embarrassing", shared-memory and distributed-memory parallelism
- Know the basics of parallel workflows, multiprocessing, multithreading and MPI
- Understand pre-compilation and know basic usage of Numba and Cython
- Have a mental model of how Dask achieves parallelism
- Remember key hardware differences between CPUs and GPUs
- Be able to create simple GPU kernels with Numba

**[Julia for High Performance Scientific Computing](https://enccs.github.io/julia-for-hpc/)**

- Experienced practitioners in other languages understand what's different/special about Julia
- Become familiar with typical structure of a Julia package
- Set up efficient workflow for developing in Julia and using the package manager
- Learn to efficiently work with data 
- Know what performance pitfalls exist and learn to benchmark and profile code
- Learn to use multithreading and distributed computing
- Understand what different approaches exist for porting code to GPUs

**[Julia for High Performance Data analytics](https://enccs.github.io/julia-for-hpda/)**

- Learn how to work with and visualise datasets in Julia using DataFrames.
- Understand how to perform vector and matrix operations effectively in Julia.
- Become familiar with regression, time-series prediction and analysis.
- Get an overview of packages in Julia for classical machine learning and deep learning.
- Be able to fit simple ML and DL models to datasets. 


## AI

**[Upscaling AI training](https://enccs.github.io/upscaling-ai-training/)**

- Learn different strategies to perform distributed training in TensorFlow
- Learn how to use Horovod for distributed training
- Learn to containerise neural network training

**[A.I. as a Tool for Change](https://www.youtube.com/watch?v=_FMnopQNF3M)**

- Get an overview of possible use cases for artificial intelligence
- Understand how AI can effectively be put to use in different sectors and application domains
 

**[Graph Neural Networks and Transformer](https://enccs.github.io/gnn-transformers/)**

- Learn to use graph neural networks
- Learn to use transformers

## Applications

**[Gromacs GPU Performance](https://enccs.github.io/gromacs-gpu-performance/)**

- Understand the difference between MPI ranks and OpenMP threads when running GROMACS
- Be able to name the most important parts of the molecular dynamics workflow
- Appreciate some of the internal architecture of mdrun
- Know how to assign the PME workload
- Know how to use several GPUs efficiently.
- Know common pitfalls to avoid


**[VeloxChem: Quantum chemistry from laptop to HPC](https://enccs.github.io/veloxchem-workshop/)**

- Learn to perform quantum chemical simulations of ground- and excited-state properties of large systems using VeloxChem.
- Leverage the aggregate resources of modern HPC clusters to efficiently tackle large molecular systems.
- Use the Python application programming interface (API) to prototype new methods.
- Design interactive computational teaching materials in Python.

**[TREX: Targeting chemical accuracy with quantum Monte Carlo on LUMI](https://trex-coe.github.io/school-ncc-2023/index.html)**

- Get acquainted with the basic theory behind Quantum and Variational Monte Carlo methods, and multideterminant wave functions.
- Learn how to combine the Quantum Package DFT code with the CHAMP QMC code to perform highly accurate electronic structure calculations.
- Become comfortable running Quantum Package and CHAMP in an HPC environment.

**[MAX: Efficient materials modelling](https://enccs.github.io/efficient-materials-modelling-on-hpc/)**

- Learn how to launch the most common types of calculations (e.g. scf, phonons, quasi-particle energies, time-dependent properties) using QE, Yambo and BigDFT 
- Learn how to prepare input files and how to read output files in order to extract the desired properties.
- Get an overview of best practices for efficient exploitation of HPC resources. 
- Learn how to use the different schemes of data distribution (e.g. plane waves, pools, images) in combination with the different parallelization and acceleration schemes (MPI, OpenMP, GPU-offload) available in Quantum Espresso.

**[Developing Applications with the AMD ROCm Ecosystem](https://enccs.github.io/amd-rocm-development/)**
 
- Learn how to develop and port applications to run on AMD GPU hardware on top AMD-powered supercomputers. 
- Learn about the ROCm software development languages, libraries, and tools 
- Get a developer’s view of the hardware that powers the system. 

**[VASP best practices](https://enccs.github.io/vasp-best-practices/)**

- Learn several best practices for running VASP efficiently on HPC.
- Remember basic theory of DFT and the PAW-method.
- Larn about essential files and parameters in VASP. 
- Become comfortable with workflows for running VASP at HPC centers, on both CPUs and GPUs
- Learn basics of performance analysis and post-processing tools. 
- Understand common issues that can arise when running VASP. 



**[OpenFOAM](https://enccs.github.io/openfoam/)**

- Learn how to use OpenFOAM.

## Tools

**[CMake](https://enccs.github.io/cmake-workshop/)**

- Write a CMake build system for C, C++, and Fortran projects producing libraries and/or executables.
- Run tests for your code with CTest.
- Ensure your build system will work on different platforms.
- Detect and use external dependencies in your project.
- Safely and effectively build mixed-language projects (Python+C/C++, Python+Fortran, Fortran+C/C++)

**[Containers](https://enccs.github.io/containers/)**

- Learn to use Docker
- Learn to use Singularity

## Quantum computing

**[Introduction to Quantum Computing and hybrid HPC-QC systems](https://enccs.github.io/nordiquest-workshop/)**

- Learn key concepts: quantum states, qubits, quantum algorithms
- Get an overview of QC programming in high-level languages for use cases in optimisation, finance and quantum chemistry 
- Get an overview of the main QC hardware approaches
- Understand how QC can be integrated with classical computing through hybrid classical/quantum algorithms and HPC-QC systems.
- Learn to perform quantum software testing with the Quito tool

```{discussion}
- Are there any lessons in the list above that you would like to use in your own teaching?
- (After the instructor gives an overview of one of the lessons) What do you think about this 
  lesson format? How does it compare to training material that you use?
```

## Recommended external resources

The lessons above do not cover all relevant topics in HPC, HPDA and AI, but 
ENCCS also maintains a list of recommended public training material which you 
can find at [https://enccs.se/external-training-resources/](https://enccs.se/external-training-resources/).

```{challenge} Contribute to the list of external training resources 
**For after this workshop:**  
If you know of other good public training material, or if you have developed own material 
that you would like to share with the world, please [get in touch](https://enccs.se/contact/) or 
[open an issue](https://github.com/ENCCS/instructor-training/issues) on this repository!
```


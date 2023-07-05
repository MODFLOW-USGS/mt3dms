# MT3DMS version 5.3
A Modular 3-D Multi-Species Transport Model for Simulation of Advection, Dispersion, and Chemical Reactions of Contaminants in Groundwater Systems
MT3DMS is the second generation of the modular three-dimensional transport model MT3D.  MT3DMS was developed with funding from the U.S. Army Corps of Engineers Waterways Experiment Station under the Strategic Environmental Research and Development Program (SERDP).  

MT3DMS has significantly expanded capabilities, including the addition of, 1) a third-order total-variation-diminishing (TVD) scheme for solving the advection term that is mass conservative but does not introduce excessive numerical dispersion and artificial oscillation; 2) an efficient iterative solver based on generalized conjugate gradient methods and the Lanczos/ORTHOMIN acceleration scheme to remove stability constraints on the transport time stepsize; 3) options for accommodating nonequilibrium sorption and dual-domain advection-diffusion mass transport; and 4) a multi-component program structure that can accommodate add-on reaction packages for modeling general biological and geochemical reactions.  

Additional information on MT3DMS can be found at [https://hydro.geo.ua.edu/mt3d/index.htm](https://hydro.geo.ua.edu/mt3d/index.htm).

--------------------------

Downloaded as a self-extracting executable file (`mt3dms_530.exe`) on July 3, 2023 from [https://hydro.geo.ua.edu/mt3d/index.htm](https://hydro.geo.ua.edu/mt3d/index.htm).

This repository was created to facilitate automatic builds of MT3DMS used in GitHub Actions CI workflows. Only the source files in the `mt3dms5.3.0/src/true-binary/` subdirectory available in the self-extracting executable file (`mt3dms_530.exe`), available from [https://hydro.geo.ua.edu/mt3d/index.htm](https://hydro.geo.ua.edu/mt3d/index.htm), have been included in this repository.

# OpenMP-MPI-Offloading-Example

This is a subroutine from a massively parallel OpenMP/MPI implementation of an analytic gradient for the quantum chemistry method CCSD(T). The general algorithm splits work across a user defined (ideally 1) MPI rank per computer node and spawns a user defined number of OpenMP threads per MPI rank (ideally the number of cores per computer node). This effectively parallelizes the large amount of computational work associated with the expensive CCSD(T) method. 

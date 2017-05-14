# Jacobi iteration

In this exercise we will implement a Jacobi iteration that is a very simple
finite-difference scheme. Familiarize yourself with the provided skeleton.
Then implement following things:

1. Write the missing CUDA kernel `sweepGPU` that implements the same algorithm
   as the sweepCPU function. Check that the reported averate difference is in
   the order of the numerical accuracy.
2. The skeleton provides the timing calls for the CPU part. Implement timing
   for the GPU part by adding the needed CUDA event routine calls.
3. Experiment with different grid and block sizes and compare the execution times.
## Optimization of Sparse Deep Neural Networks using GPU


- Sparse DNNs were introduced to lower memory usage, but keep the performance equivalent to DNNs.
- The Graph Challenge focuses on optimizing calculations for sparse DNNs.

Optimizations:
- Pinned memory replaced paged memory for faster GPU loading of layer matrix W.
- Kernel function optimized with shared memory and tiling.
- Two arrays used for empty rows and non-zero values in input matrix Y to skip unnecessary computations during multiplication.

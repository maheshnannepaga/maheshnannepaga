# Hi, I'm Mahesh

### C++ performance engineering · HPC · GPU computing

I'm building toward GPU-accelerated computing and HPC roles through hands-on work in numerical kernels, correctness validation, and reproducible benchmarking.

My current focus is **HPC Performance Lab**: a C++20 matrix multiplication benchmark that explores how memory access patterns and cache blocking affect performance.

## Featured project

### [HPC Performance Lab](https://github.com/maheshnannepaga/hpc-perf-lab)

A GEMM benchmark suite built around a simple principle: validate correctness before comparing performance.

- **Implemented:** configurable cache-blocked C++20 GEMM, a reference implementation, deterministic inputs, and CSV benchmark output.
- **Reproducibility:** build and smoke-test automation with GitHub Actions, a Dockerfile, and a Slurm batch script.
- **Performance methodology:** document workload, hardware, compiler settings, repetitions, and validation status alongside reported measurements.
- **Next milestones:** publish baseline measurements, evaluate OpenMP scaling, and extend the same workload to CUDA and MPI.

[Explore the code](https://github.com/maheshnannepaga/hpc-perf-lab) · [Benchmark methodology](https://github.com/maheshnannepaga/hpc-perf-lab/blob/main/docs/experiment-plan.md)

## Technical focus

| Area | Current work and direction |
| --- | --- |
| CPU performance | C++20, cache blocking, numerical correctness, GEMM benchmarking |
| HPC workflows | Slurm batch scripts, reproducible runs, containerized builds |
| Engineering practices | GitHub Actions, smoke tests, deterministic validation |
| GPU and parallel computing | Planned CUDA GEMM implementation, OpenMP scaling studies, and MPI experiments |

## What I'm working toward

- Measure CPU baseline performance across matrix and tile sizes.
- Compare serial and OpenMP implementations with documented hardware and thread counts.
- Implement CUDA GEMM and compare a basic kernel with shared-memory tiling.
- Report GPU kernel time separately from end-to-end time, including data transfers.
- Document measured results, limitations, and optimization tradeoffs.

I'm interested in opportunities focused on **GPU-accelerated computing, HPC, and performance engineering**.

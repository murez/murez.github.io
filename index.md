---
layout: homepage
---

## About Me

I am a graduate student from Shanghaitech University. I am looking for PhD position in 24 Spring and 24 Fall in the field of HPC and MLsys.

## Research Interests

- **HPC** : MPI, GPU, HPC4AI
- **MLSys**

## Experience

### Research Assistant @ **L.I.O.N.** & **NeuDim**

Co-author [*NEPHELE*: A Neural Platform for Highly Realistic Cloud Radiance Rendering](https://arxiv.org/pdf/2303.04086.pdf), as the second author.

- Reduce hash grid size by 8.7 times by introducing *Perfect Spatial Hashing* into NGP.
- Develop a multi-GPU, multi-node extrem low latency NGP rendering framework, achieving 50 FPS @ 1080 resolution for 12 NGP on 4 GPUs in one node and 37 FPS @ 1080 resolution for 12 NGP on 4 GPUs in 2 nodes using **CUDA awared MPI**.


### Student Cluster Competition (SCC) @ Geekpie_HPC Shanghaitech University

High Performance Computing (HPC) related research. Continually preparing and aiming for the top-tier student supercomputing competitions, including ASC, ISC and SC. Mainly in charge of HPC tasks related with AI, MPI and CUDA.

- **ASC22** @ USTC : 
  - Manage hardwares under restricted power constraints (3KW, 3 nodes, 8 GPUS).
  - Use DeepSpeed to accelerate of YUAN A Large Language Model Pretrain Model.
  - Fine-tuned HPC benchmarks *HPCG* and *HPL*.

  
- **ISC22** @ Online :
 - Profile and optimize *ICON* a MPI Program for earth system model (3rd place).


- **SC21** @ Online (2nd place):
  - Reproduce the correctness of a SC research *ramBLe* (1st place).
  - Run and tuning a multi-node multi-GPU DNN image segmentation application *CosmicTagger*. (2nd place).

- **ISC21** @ Online:
  - Modify a GPU optimized *HPCC* benchmark
  - Research on MPI and OpenMP balance for *WRF*
  - Contributed for collective_profiler a set of tools and libraries to profile Alltoallv MPI calls.

### Teaching Assistant

CS171: Computer Graphics ShanghaiTech University 

### Skills

#### Programming Languages

C/C++, CUDA, Python

#### Frameworks, Libs

OpenMP, MPI, Pytorch, OpenGL, OpenCV


#### Tools

Nsight System, Nsight Compute, Intel Vtune, Intel Trace Analyser and Collector, IPM.


{% include_relative _includes/publications.md %}

{% include_relative _includes/services.md %}

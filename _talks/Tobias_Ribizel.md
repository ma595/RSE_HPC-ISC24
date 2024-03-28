---
name: Lightning Fast and Flexible Continuous Integration for HPC Software
speakers:
  - Tobias Ribizel
categories:
  - HPC-RSE
  - Talk
---

Smooth software development workflows in teams depends on rapid turnaround times of the involved steps - development, continuous integration and code reviews. In the context of the development of the Ginkgo library for numerical linear algebra, we observed regularly that continuous integration pipelines are our major bottleneck, especially when multiple developers are working on different projects in the same code base, or when a series of pull requests depend on each other. We want to show the evolution of our gitlab runner-based continuous integration pipelines across multiple GPU vendors, architectures and compiler versions, container image management, scaling out from a single machine to multiple machines, moving onto HPC systems using rootless containers, and finally optimizing for build and test performance. We will talk about a custom executor developed for the gitlab runners to enable the use of HPC systems with SLURM and Apptainer for consistent build environments, and some thoughts on how a generic gitlab-runner executor could be structured for use in a wide range of HPC contexts.
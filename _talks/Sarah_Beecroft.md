---
name: AlphaFold x AMD - Uniting Diverse Expertise for Breakthrough Computational Biology
speakers:
  - Sarah Beecroft 
categories:
  - HPC-RSE
  - Talk
---

Computational structural biology is in the midst of a titanic shift in capability: one led by tools like AlphaFold2, which allows virtually any researcher to predict any novel protein structure and access vast archives of pre-computed structures available through UniProt (EMBL-EBI). This would have previously taken years of laborious experimentation.

A key issue in democratising access to AlphaFold2 is that the NVIDIA GPUs required can be difficult to source and access, as they are limited in number and highly sought after. Commercial cloud resources are restrictive for researchers in accessibility and price. This resourcing challenge can be met by porting AlphaFold2 to other GPUs, thereby expanding the resources available to support this software. Achieving this is a significant challenge that requires interdisciplinary collaboration.

Here, we describe a national collaboration between the Australian Computational Structural Biology community, Pawsey Supercomputing Research Centre, UNSW, AMD, and the Australian BioCommons. This group brings together skills in GPU hardware, containerisation of a complex software stack, moving to ROCM compatible dependencies, scaling testing, and scientific validation of results. This unique combination of HPC, RSE, and scientific domain knowledge is required to ensure that AlphaFold2, and other tools (e.g. FastFold), can run on AMD GPUs. Importantly, this included a community assessment that confirms the delivery of meaningful outputs for life scientists.
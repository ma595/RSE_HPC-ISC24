---
name: Software engineering for validating finite-temperature XC-functional
speakers:
  - Mani Lokamani
categories:
  - HPC-RSE
  - Talk
---

In recent years, density functional theory (DFT) has revolutionzed simulations in the domain of warm dense matter (WDM) which focuses on unraveling behavior of matter in fusion reactor, planetary interiors and other areas of high energy physics. The success of DFT relies on accurate approximations of the exchange-correlation (XC) effects based on exact quantum monte carlo (QMC) results. In this contribution, we summarize our recent work toward improving XC at finite temperatures, which is called thermal PBE[1] and incorporting the improvements in LIBXC[2], a library widely used in the material science community. We highlight the software engineering challenges in the field of high performance computing including: (i) deployment of continuous integration (CI) using Gitlab runners, (ii) incorporating containers for CI and reproducibility and (iii) refactoring strategies. We also highlight the importance of research software engineering (RSE) for validating accurate utilization of community high-performance-computing codes.

References

[1] https://doi.org/10.48550/arXiv.2308.03319
[2] https://doi.org/10.1016/j.softx.2017.11.002
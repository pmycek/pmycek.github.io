---
title: "Research"
permalink: /research/
---

## Main research interests

* Uncertainty quantification (UQ)
  * Monte Carlo (MC) methods
  * Multifidelity estimation and modeling
  * Surrogate modeling
  * Sensitivity analysis
* Numerical linear algebra
  * Krylov subspace methods
  * Preconditioning and deflation techniques
  * Multigrid methods
  * Domain decomposition methods
* High performance computing (HPC)
* Computational fluid dynamics (CFD)
* Particle methods




## Habilitation à diriger des recherches (HDR thesis) {#hdr}

### Manuscript {#hdr-manuscript}

My HDR manuscript is openly available on [TEL](https://hal.science/tel-04521927).

### Abstract

Hierarchical methods have become essential tools for the efficient numerical simulation of physical phenomena with ever-growing fidelity on modern high-performance supercomputers.
Well-established methods, such as multigrid and domain decomposition methods, owing to their scaling capabilities, have proven powerful to solve certain classes of large-scale problems in a parallel fashion on supercomputers.
On the other hand, the propagation of uncertainties in numerical simulations has received increasing attention in recent years.
For computationally demanding simulations of highly non-linear problems (w.r.t. uncertain input parameters), advanced uncertainty quantification methods need to be designed.
In this manuscript, we present methodological and algorithmic ideas to address specific questions related to hierarchical methods.
First, we present resilient domain decomposition approaches for the numerical solution of deterministic and stochastic partial differential equations, as well as surrogate-assisted Monte Carlo strategies for the propagation of uncertainties in domain decomposition solvers.
Second, we introduce novel multigrid solvers for the linear systems arising from hybridizable high-order discretizations.
Third, we propose hierarchical approaches, namely multilevel and multifidelity methods, for the propagation of uncertainties in expensive numerical simulators.
Finally, we also propose ideas for the efficient numerical solving of sequences of systems of linear equations that typically arise when solving time-dependent and/or non-linear problems, or when sampling stochastic partial differential equations.



## Ph.D. thesis {#thesis}

### Manuscript {#manuscript}

My Ph.D. manuscript is openly available:

* [TEL][these_TEL] (multidisciplinary theses server).
* [Archimer][these_Archimer] (IFREMER's bibliographic archives).

[these_TEL]: http://tel.archives-ouvertes.fr/tel-00925229
[these_Archimer]: http://archimer.ifremer.fr/doc/00170/28152/

### Abstract

<img class="img-hydrol" src="{{ 'images/1hydrol_haute_def.png' | relative_url }}" alt="Modélisation du sillage d'une hydrolienne par la méthode Vortex" />

This manuscript deals with the numerical and experimental characterisation of the behaviour of marine current turbines. In the experimental part, trials were run at IFREMER's wave and current flume tank in Boulogne-Sur-Mer, on prototypes of three-bladed horizontal axis turbines. Configurations with one single turbine on the one hand, and two turbines aligned with the incoming flow on the other hand, were considered for a large range of TSRs and, when relevant, of inter-device distances. The behaviour of the turbines is analysed in terms of performances (power and thrust coefficients) and development of the wake. The effects of the ambient turbulence intensity rate are also considered. Besides, numerical computations, obtained from a tridimensional unsteady software, based on the Vortex particle method and developed at the LOMC (UMR 6294, CNRS - University of Le Havre) in partnership with IFREMER, are presented. The numerical tool also enables to study the performances and the wake of a turbine. It was rewritten during this PhD and its technical and theoretical support is available in the manuscript, where the Vortex method, as it is used in the software, is described in details.

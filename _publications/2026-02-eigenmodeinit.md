---
title: "Eigenmode initialisation of 2D (magneto)hydrodynamic simulations"
collection: publications
permalink: /publication/2026-02-eigenmodeinit
excerpt: ""
date: 2026-02-22
venue: "Astronomy & Astrophysics"
paperurl: ""
citation: "De Jonghe, J. and Russell, A. J. B. (2026). &quot;Eigenmode initialisation of 2D (magneto)hydrodynamic simulations.&quot; <i>Astron. Astrophys.</i> Accepted 22 February 2026."
---

__Abstract.__

_Aims._ The early evolution of unstable hydrodynamic and magnetohydrodynamic equilibria is often governed by a few dominant linear eigenmodes. We investigate whether initialising a simulation with a superposition of linear eigenmodes that contains the most unstable mode saves computation time, and how the selection of the included modes affects the non-linear evolution. Three 2D setups are considered, each representative of a distinct non-linear behaviour: a flow-sheared fluid interface (density gradient) unstable to the Kelvin-Helmholtz instability, to study the effect of the initial perturbation on developing turbulence; a tearing-unstable Harris current sheet, to investigate how the initial perturbation affects secondary instabilities; and a magnetised flow-sheared plasma interface that is linearly unstable, but where magnetic tension suppresses the instability again in the non-linear phase.
_Methods._ Using the non-linear (magneto)hydrodynamic simulation code [MPI-AMRVAC](https://amrvac.org), the evolutions of a flow-sheared fluid interface, a Harris current sheet, and a flow-sheared plasma interface are simulated for various initial perturbations. The novel initial perturbations are linear eigenmodes of the equilibrium, or superpositions thereof, calculated with the [Legolas](https://legolas.science) code. We benchmark to initialisation with velocity noise and, in the case of the Harris sheet, initialisation with an analytic magnetic field perturbation.
_Results._ By perturbing an unstable equilibrium with a superposition of linear eigenmodes that contains the most unstable mode, significantly less computation time is spent on the linear stage of the evolution compared to traditional perturbation methods. In the best case, the simulation time needed to reach the non-linear stage was reduced by an order of magnitude. The inclusion or omission of certain modes in the initial perturbation was observed to affect the non-linear evolution to various degrees.
_Conclusions._ The perturbation of equilibria with a superposition of linear eigenmodes that contains the most unstable mode allows simulations to reach a late-evolution stage faster, thus saving computation time. Additional eigenmodes can be included alongside the fastest growing mode to obtain further benefits, for example, to accelerate symmetry breaking in the non-linear stage, or to delay their effect on the non-linear evolution. Coupling spectroscopic codes with (magneto)hydrodynamic codes therefore offers significant advantages to the astrophysics community.

<!-- Preprint - []() -->

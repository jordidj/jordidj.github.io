---
title: "GIMLI: connecting magnetohydrodynamic MPI-AMRVAC simulations to spectroscopy with the Legolas code"
collection: talks
type: "Contributed talk"
permalink: /talks/2026-astronum
excerpt: ""
venue: "ASTRONUM"
date: 2026-07-01
location: "Bordeaux, France"
---

Contributed talk at ASTRONUM 2026, Bordeaux, France.

__Abstract.__ The General Interface for MPI-AMRVAC / Legolas Interconnection, or GIMLI for short, is a Python-based framework, alongside a handful of Fortran routines for MPI-AMRVAC and the Legolas code, with three main functionalities: (1) generating user modules for the MPI-AMRVAC simulation code and the spectroscopic Legolas code from a single definition of a one-dimensionally varying state; (2) extracting Legolas eigenmode solutions for use as initial perturbations in MPI-AMRVAC simulations; and (3) performing spectroscopic analysis of 1D simulation data (e.g. 1D slices of MPI-AMRVAC data) with the Legolas code. The first functionality minimizes room for user error when setting up both codes to study the same configuration. The second point allows tighter control over simulations' initial perturbations than traditional methods and, for unstable configurations, reduces the simulation time spent in the non-linear stage. Finally, the last part of the code provides a way to perform eigenmode analysis on simulation data, allowing the user to interpret a simulation's dynamics from an eigenmode perspective.

---
title: "Efficient parameter studies with the Legolas code and connecting to non-linear simulations"
collection: talks
type: "Contributed talk"
permalink: /talks/2024-smtgcodeforum
excerpt: ""
venue: "SMTG Code Forum"
date: 2024-04-18
location: "St Andrews, United Kingdom"
---

Contributed talk at the SMTG Code Forum, St Andrews, United Kingdom. Part of the Organising Committee.

__Abstract.__ [Legolas](https://legolas.science) is a (magneto)hydrodynamic code that quantifies all natural oscillations and instabilities of a one-dimensionally varying force-balanced state. Thanks to its low computational cost, data can be generated efficiently for large parameter spaces. To analyse large volumes of data equally efficiently, we can rely on neural networks to perform the classification of eigenmodes to high accuracy. Additionally, the linear perturbations calculated by Legolas are used to initialise simulations with MPI-AMRVAC, considerably speeding up the convergence to an island structure for a tearing Harris sheet.
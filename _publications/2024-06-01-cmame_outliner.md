---
title: "A robust finite strain isogeometric solid-beam element"
collection: publications
permalink: /publications/2024-06-01-cmame_outliner
excerpt: 'Computer Methods in Applied Mechanics and Engineering, June 2024. Read more.'
---

<div class="small">
   Computer Methods in Applied Mechanics and Engineering, June 2024.
</div> <br />

<div class="small">
   Authors: <u><strong>A. Shafqat</strong></u>, O. Weeger,BX. Xu. 
</div><br/>
[[doi](https://doi.org/10.1016/j.cma.2024.116993)] 

In this work, an efficient and robust isogeometric three-dimensional solid-beam finite element is developed for large deformations and finite rotations with merely displacements as degrees of freedom. The finite strain theory and hyperelastic constitutive models are considered and B-Spline and NURBS are employed for the finite element discretization. Similar to finite elements based on Lagrange polynomials, also NURBS-based formulations are affected by the non-physical phenomena of locking, which constrains the field variables and negatively impacts the solution accuracy and deteriorates convergence behavior. To avoid this problem within the context of a solid-beam formulation, the Assumed Natural Strain (ANS) method is applied to alleviate membrane and transversal shear locking and the Enhanced Assumed Strain (EAS) method against Poisson thickness locking. Furthermore, the Mixed Integration Point (MIP) method is used to make the formulation more efficient and robust. The proposed novel isogeometric solid-beam element is tested on several single-patch and multi-patch benchmark problems, and it is validated against classical solid finite elements and first-order Lagrange solid-beam element. The results show that the proposed formulation can alleviate the locking effects and significantly improve the performance of the isogeometric solid-beam element. With the developed element, efficient and accurate predictions of mechanical properties of lattice-based structured materials can be achieved. The proposed solid-beam element inherits both the merits of solid elements e.g. flexible boundary conditions and of the beam elements i.e. higher computational efficiency.


---
title: "A robust finite strain isogeometric chemo-mechanics solid-beam element"
collection: publications
permalink: /publications/2026-01-01-cmame_outliner
excerpt: 'Computer Methods in Applied Mechanics and Engineering, January 2026. Read more.'
---

<div class="small">
   Computer Methods in Applied Mechanics and Engineering, January 2026.
</div> <br />

<div class="small">
   Authors: <u><strong>A. Shafqat</strong></u>, O. Weeger,BX. Xu. 
</div><br/>
[[doi](https://doi.org/10.1016/j.cma.2025.118457)] 

An efficient isogeometric solid-beam element for finite strain chemo-mechanical analysis is presented in this work. The formulation is particularly well-suited for simulating diffusion-induced large deformations and buckling of slender micro-lattice structures, such as micro-architected Li-ion battery electrode materials. This multi-field solid-beam element extends our previous work by fully coupling chemical diffusion, finite volumetric chemical expansion, and large elastic deformations. The mechanics driven drifting effect on the flux of the chemical species induces higher-order issue. Consequently, a mixed formulation with displacements, concentration and chemical potential as degrees of freedom is employed. The two-way coupled variational problem is discretized using NURBS basis functions. As with solid finite elements based on Lagrange polynomials, NURBS-based formulations are also affected by the non-physical phenomena of locking. To mitigate such effects in the solid-beam context, the assumed natural strain (ANS) method is employed to alleviate both membrane and transverse shear locking, while quadratic or higher-degree NURBS along the beam’s cross-section naturally alleviate Poisson thickness locking. Additionally, a mixed integration point (MIP) strategy is adopted to enhance computational efficiency and robustness. The proposed element is evaluated through a series of single-patch and multi-patch benchmark problems, and validated against a coupled 3D chemo-mechanical solid element. Results demonstrate that the developed solid-beam element inherits the high accuracy typical of solid elements, while also offering the computational efficiency and locking-alleviation performance characteristic of slender beam analysis. This element offers a promising tool for robust simulations of eigenstrain-induced large deformations and buckling of slender structures within a multi-physics framework like chemo-mechanics and thermo-mechanics.
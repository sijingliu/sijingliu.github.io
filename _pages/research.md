---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}



As a computational mathematician, my research focuses on the development and rigorous analysis of numerical algorithms. I specialize in designing efficient and robust methods for approximating solutions to partial differential equations (PDEs) or systems of PDEs. I am generally interested in the following research fields:

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <ul>
      <li>Multigrid methods</li>
      <li>PDE-constrained optimization, optimal control problems</li>
      <li>(Stabilized) finite element methods, discontinuous Galerkin methods</li>
      <li>Convection-dominated problems</li>
      <li>Fluid-structure interaction</li>
      <li>Scientific machine learning</li>
    </ul>
  </div>
  <div style="flex: 0.25; text-align: center;">
    <figure style="width: 100%;">
      <img src="/images/mg.png" alt="Multigrid" style="width: 100%;" />
      <figcaption style="text-align: center;">Multigrid</figcaption>
    </figure>
  </div>
</div>



Research Projects:
======
* Finite element methods and multigrid methods for optimal control problems.
  * We have designed and analyzed new finite element methods (continuous Galerkin and Discontinuous Galerkin) and multigrid methods for elliptic optimal control problems (with pointwise state constraints). We are now particularly interested in designing finite element methods and multigrid methods for elliptic optimal control problems constrained by convection-diffusion-reaction equations (with pointwise state constraints), especially in the convection-dominated regime. 


   <div style="display: flex; justify-content: center; gap: 20px;">
    <figure style="width: 45%; text-align: center;">
      <iframe src="/assets/OptimalControlwithStateConstraints.html" width="80%" height="350px" style="border: none;"></iframe>
      <figcaption style="text-align: center;">The State</figcaption>
    </figure>
    <figure style="width: 45%; text-align: center;">
      <iframe src="/assets/OptimalControlwithStateConstraints1.html" width="80%" height="350px" style="border: none;"></iframe>
      <figcaption style="text-align: center;">The Control</figcaption>
    </figure>
  </div>



* Fluid-Structure interaction problems.
  * We are also interested in fluid-structure interaction problems. These are multiphysics problem that consists of a fluid problem and a solid problem that interact with each other through an interface. We are particularly interested in Robin-Robin loosely coupled methods, as well as in designing new loosely coupled methods that exhibit higher convergence rates.

* Dual-wind discontinuous Galerkin methods for convection-dominated problems.
  * Dual-wind discontinuous Galerkin (DWDG) methods are new discontinuous Galerkin (DG) methods that are derived from a DG differential calculus framework. This framework recovers existing DG methods and also advises construction of new DG methods.

* BDDC preconditioner with Hybridizable discontinuous Galerkin methods (HDG) for optimal control problems
 
  


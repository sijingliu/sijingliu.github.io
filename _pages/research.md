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
* Efficient numerical methods for optimal control problems.
  * We have designed and analyzed new finite element methods (continuous Galerkin and Discontinuous Galerkin) and multigrid methods for elliptic optimal control problems (with pointwise state constraints). We are now particularly interested in designing finite element methods and multigrid methods for elliptic optimal control problems constrained by convection-diffusion-reaction equations (with pointwise state constraints), especially in the convection-dominated regime. 

  * We have investigated the following numerical methods and their corresponding fast solvers:
    * Discontinuous Galerkin methods
    * Hybridizable discontinuous Galerkin methods
    * Edge-averaged finite element methods

  <!--  <div style="display: flex; justify-content: center; gap: 10px;">
    <figure style="width: 45%; text-align: center;">
      <iframe src="/assets/OptimalControlwithStateConstraints.html" width="500px" height="500px" style="border: none;"></iframe>
      <figcaption style="text-align: center;">The State</figcaption>
    </figure>
    <figure style="width: 100%; text-align: center;">
      <iframe src="/assets/OptimalControlwithStateConstraints1.html" width="100%" height="100%" style="border: none;"></iframe>
      <figcaption style="text-align: center;">The Control</figcaption>
    </figure>
  </div> -->

<div style="display: flex; justify-content: flex-start;">
    <figure style="width: 80%; text-align: left;">
      <iframe src="/assets/OptimalControlwithStateConstraints1.html" width="100%" height="500px" style="border: none;"></iframe>
      <figcaption style="text-align: center;">The Control</figcaption>
    </figure>
  </div>

* Fluid-Structure interaction problems.
  * We are also interested in fluid-structure interaction problems. These are multiphysics problem that consists of a fluid problem and a solid problem that interact with each other through an interface. We are particularly interested in Robin-Robin loosely coupled methods, as well as in designing new loosely coupled methods that exhibit higher convergence rates.

  <div style="display: flex; justify-content: center;">
    <figure style="width: 70%; text-align: center;">
      <img src="/images/fsi.png" alt="Fluid-Structure Interaction" style="width: 100%;" />
      <figcaption style="text-align: center;">Robin-Robin loosely coupling</figcaption>
    </figure>
  </div>

* Dual-wind discontinuous Galerkin methods for convection-dominated problems.
  * Dual-wind discontinuous Galerkin (DWDG) methods are new discontinuous Galerkin (DG) methods that are derived from a DG differential calculus framework. This framework recovers existing DG methods and also advises construction of new DG methods.

* Physics-informed neural networks (PINNs) for optimal control problems with convection-dominated state equations.
  * PINNs incorporate PDEs into the loss function of neural networks to solve PDEs. We are interested in using PINNs to solve a saddle-point formulation of an optimal control problem with convection-dominated state equations. To tackle this challenging problem, we exploit a recently developed two-scale neural network.

 
  


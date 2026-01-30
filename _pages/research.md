---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---
Manifold Learning on Crystal Plasticity Data
-----
Jun. 2024 - Present

**Advisor: [Kaushik Bhattacharya](https://mechmat.caltech.edu/), Professor of Mechanical Engineering, California Institute of Technology**
* Built a parallel C++ simulation to generate large-scale magnesium plasticity datasets under varying loadings.
* Designed and trained an autoencoder to learn low-dimensional manifold structure of high-dimensional plasticity fields and enable low reconstruction error (<10%) at thin bottleneck dimension (<10).
* Trained a neural operator to predict the average stress response from deformation gradient history.
* Analyzed effects of data resolution, grain distribution, and loading paths on reconstruction accuracy.
   
<div>			
    <img src="/keyangyang.github.io/images/AE_crystal.png"
         width=700>
    <br>
    Figure. 1. Spatial resolution of crystal plasticity data affects the reconstruction error.
<br>

Inference of Interatomic Potential from Atomic Configurations
-----
Jun. 2025 - Present

**Advisor: [Kaushik Bhattacharya](https://mechmat.caltech.edu/), Professor of Mechanical Engineering, California Institute of Technology**
* Formulated an optimization framework to infer interatomic potentials directly from TEM observations.
* Extended JAX-MD with 10+ custom modules for molecular statics simulation and customized energy functions.
* Reduced computation time of Hessian matrix of energy function by 90% compared to auto differentiation.
* Performed model selection and gradient-based parameter optimization on experimental data.
* Derived average atomic positions at finite temperature of candidate potentials from statistical mechanics.

Simulation of Ring Origami Structures with Larger Packing Ratios
-----
Jun. 2022 - Nov. 2022

**Advisor: [Renee Zhao](https://profiles.stanford.edu/264302), Assistant Professor of Mechanical Engineering, Stanford University**
* Created ABAQUS models to simulate the packing process of ring origami structures with different shapes
* Developed Python programs for parametric modeling, data export and post-processing
* Obtained the relationship between the loading curves and the geometric parameters, loading positions,
cross-sectional shapes, etc. during the folding process
   
<div>			
    <img src="/keyangyang.github.io/images/figure4.png"
         width=700>
    <br>
    Figure. 1. FEA simulation of ring origami. (a) Geometrical structure and parameters of ring origami. (b) One of the loading methods. (c) Isometric view of the ring during the folding process.
</div>    
<br>

<div>			
    <img src="/keyangyang.github.io/images/figure5.png"
         width=700>
    <br>
    Figure. 2. Loading phase diagram for different combinations of geometrical parameters. The normalized moment MR/EJ is independent of the R/t values, which can be explained by quantitative analysis.
</div>    
<br>

Instability Analysis of Active Soft Material Spherical Shell
-----

Sep. 2021 - Jun. 2022   

**Advisor: [Bo Li](https://www.hy.tsinghua.edu.cn/hyen/info/1162/1222.htm), Associate Professor of Aerospace Engineering, Tsinghua University**
* Applied the theory of active soft matter to the instability morphology problems in biological systems
* Set up a model of active soft spherical shell, derived the governing equations of shell surface instability using
different active material theories and numerically solved the instability morphology with COMSOL
* Explained the relationship between morphogenesis and defects during the regeneration of hydroids

<div>			
    <img src="/keyangyang.github.io/images/figure3.png"
         width=800>
    <br>
    Figure. 3. Surface instability of the spherical shell obtained from the simulation.
</div>    
<br>   
   
Realization of Macro-scale Superlubricity Based on Micro-Contacts
-----

Sep. 2021 – Dec. 2021   

**Advisor: [Ming Ma](https://me.tsinghua.edu.cn/en/info/1054/1328.htm), Associate Professor of Mechanical Engineering, Tsinghua University**
* Constructed tens of superlubric systems at the graphite/2D materials (graphite, WS2, SiO2) interface
* Assembled several micro-scale superlubric contact to expand the area of the superlubric system
* Developed a new method to connect micro graphite flakes with PDMS and determined the optimal experimental
parameters in preparation of PDMS film
* Simulated the deformation of PDMS film under a given load with COMSOL

<div>			
    <img src="/keyangyang.github.io/images/figure1.png"
         width=800>
    <br>
    Figure. 4. Solution to realize macro-scale superlubricity.
</div> 
<br>
   
<div>			
    <img src="/keyangyang.github.io/images/figure2.png"
         width=500>
    <br>
    Figure. 5. The PDMS film I prepared (a) before optimization and (b) after optimization. The thickness of the film is reduced to less than 1 micron.
</div> 
   

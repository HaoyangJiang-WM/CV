# Haoyang Jiang — Research Profile

**Ph.D. Student in Data Science, William & Mary**  
Scientific Machine Learning · Physical AI · Neural Operators · Inverse Problems · Spatiotemporal Modeling

## Research Focus

I work on **scientific machine learning for physical systems**, with an emphasis on combining physical structure with learning for simulation, spatiotemporal dynamics, inverse problems, and partially observed systems. My recent work spans physics-guided graph models, neural operators, generative priors, data assimilation, and stable long-horizon prediction.

## Core Research Themes

### Physics-Guided Simulation and Structured Dynamics

I develop learning architectures that embed physical structure directly into model updates, including directional graph operators and physics-guided refiners for transport-dominated systems. The goal is to improve stability, interpretability, and long-horizon behavior rather than relying only on black-box approximation.

### Neural Operators and Boundary-Aware Modeling

My work on **FIE-NO** formulates operator learning through Fredholm integral equations to handle complex and varying boundary conditions. Related work introduces learned boundary proxies to represent unresolved exterior influence in open physical domains and couples them with implicit or physics-refined propagation.

### Inverse Problems and Generative Priors

I study inverse modeling with learned priors, including full-waveform inversion with pretrained generative models and inference-time optimization. More broadly, I am interested in combining simulation, learned representations, and optimization to recover latent physical states or parameters from indirect observations.

### Generative Modeling for Dynamical Systems

I also work on second-order optimal-transport flow matching, where position, velocity, and acceleration are coupled through a variational formulation. This provides a route toward generative models that better reflect dynamical structure in scientific systems.

### Space Systems and Uncertainty Modeling

Earlier work included satellite trajectory modeling and orbit-error propagation under atmospheric-density uncertainty, together with engineering R&D experience in a space-technology environment. This background complements my broader interest in physical modeling, uncertainty, and learning-based simulation.

## Selected Publications

### IEEE ICDM 2026 — [Physics-Refined Spatiotemporal Forecasting on Open-Boundary Hydrologic Graphs](https://github.com/HaoyangJiang-WM/OpenBoundary/blob/main/ICDM_RefinedGNN.pdf)
Develops learned boundary proxies and local/global physics refinement to stabilize long-horizon prediction in open physical systems.

### TMLR 2026 — [Boundary-Consistent Graph Neural Networks for Topological Flux Prediction](https://openreview.net/forum?id=31gTIfhoH0)
Introduces ghost-node boundary closure with implicit and inverse-operator formulations for physically consistent boundary-interior coupling.

### Machine Learning: Engineering 2026 — Fredholm Integral Equations Neural Operator for Boundary Value Problems
Uses an integral-equation formulation for neural operator learning under complex and varying boundary conditions.

### ICML 2025 — [Topology-aware Neural Flux Prediction Guided by Physics](https://proceedings.mlr.press/v267/jiang25i.html)
Introduces directional, physics-guided graph operators for learning transport dynamics on networked physical systems.

### Advances in Space Research 2023 — Orbital Error Propagation Considering Atmospheric Density Uncertainty
Studies uncertainty propagation in satellite trajectory prediction under uncertain atmospheric density.

## Relevance to Physical AI and Digital Twins

My research is especially aligned with problems that require:

- coupling **simulation and machine learning** for physical systems;
- building **hybrid physics-data models** rather than purely black-box predictors;
- learning operators and reduced surrogates for repeated or real-time simulation;
- integrating observations through **data assimilation and inverse modeling**;
- maintaining stable spatiotemporal behavior over long prediction horizons;
- modeling partially observed systems with uncertain or unresolved external influence.

A unifying goal is to make learned models function as reliable computational components inside **simulation, digital-twin, and Physical AI workflows**.

---

[CV](./Haoyang_Jiang_Resume.pdf) · [GitHub](https://github.com/HaoyangJiang-WM) · [LinkedIn](https://linkedin.com/in/haoyang-jiang-7573872a4)

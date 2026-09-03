# Haoyang Jiang — Research Profile

**Ph.D. Student in Data Science, William & Mary**  
Scientific Machine Learning · Physics-Informed ML · Graph Learning · Hydrologic & Physical Systems

## Research Focus

I study how to make machine-learning models respect transport structure in open physical systems: **preserving directional dynamics, representing missing external forcing, and stabilizing long-horizon forecasts**. My recent work develops this direction through three connected studies.

## Selected Publications

### ICML 2025 — [Topology-aware Neural Flux Prediction Guided by Physics](https://proceedings.mlr.press/v267/jiang25i.html)

**Problem.** Standard graph message passing is naturally smoothing, while physical flux transport is directional. This mismatch can make GNNs insensitive to physically meaningful flow topology.

**Contribution.** We introduced directional, upwind-style graph operators and physics-guided message passing to preserve topology-sensitive flux information and distinguish physically correct forward transport from reversed topology.

### TMLR 2026 — [Boundary-Consistent Graph Neural Networks for Topological Flux Prediction](https://openreview.net/forum?id=31gTIfhoH0)

**Problem.** In open fluid networks, missing upstream context creates a boundary-context closure deficit. Prediction errors concentrate at boundary nodes rather than reflecting a fundamental lack of GNN expressivity.

**Contribution.** We proposed **gTFP**, which learns ghost-node boundary-context proxies and couples them with an implicit fixed-point formulation; an explicit inverse-operator formulation provides efficient boundary-interior propagation.

**Evidence.** Across two real-world fluid-network datasets, gTFP reduced average MSE by **8.5% and 5.4%**, boundary-node MSE by **11.0% and 6.8%**, and accelerated inference by up to **2×** depending on the backbone.

### IEEE ICDM 2026 — [Physics-Refined Spatiotemporal Forecasting on Open-Boundary Hydrologic Graphs](https://github.com/HaoyangJiang-WM/OpenBoundary)

**Problem.** Approximate or unobserved boundary forcing can continually inject error into autoregressive forecasts of open river and coastal systems, producing long-horizon drift.

**Contribution.** We combine learned ghost-node boundary proxies with a **local boundary refiner** and a **global physics refiner**. The framework addresses both *what* forcing enters an unobserved boundary and *how* that forcing should propagate without amplifying forecast error.

**Evidence.** The method is evaluated on two real hydrologic systems with different topology: the **Danube river network** and the **Chesapeake Bay unstructured mesh**. Across reported horizons, the proposed framework reduces average RMSE by **38.3%** relative to the STGNN backbone and remains effective in extreme/high-flow regimes.

## Unifying Direction

> **Directional transport → Boundary closure → Stable open-system forecasting**

The three studies form a common scientific-ML agenda: combining data-driven learning with physical structure when the modeled domain is incomplete, interacts with an unobserved exterior, and must remain stable under long-term prediction.

## Space Systems Background

Before my recent work in scientific ML for hydrologic systems, I worked on **satellite trajectory and space-system modeling**, including trajectory modeling and orbit-error propagation under **atmospheric-density uncertainty**. I also worked in a space-technology R&D environment at Origin Space, applying machine-learning and numerical methods to engineering problems. This background complements my current interest in combining physical models, observational data, uncertainty, and learning for Earth- and space-system applications.

## Relevance to Earth & Climate AI

My work is particularly aligned with:

- hydrologic and environmental forecasting on graph- and mesh-based physical domains;
- physics-aware spatiotemporal learning under missing or latent external forcing;
- scientific ML for stable simulation, forecasting, and decision-relevant Earth-system modeling;
- physical-system modeling that integrates observational data and uncertainty across Earth and space applications.

---

[CV](./Haoyang_Jiang_Resume.pdf) · [GitHub](https://github.com/HaoyangJiang-WM) · [LinkedIn](https://linkedin.com/in/haoyang-jiang-7573872a4)

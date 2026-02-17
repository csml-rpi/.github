# CSML RPI: Computational Scientific Machine Learning Lab 🚀

Welcome to the official GitHub home of the **CSML Lab** at Rensselaer Polytechnic Institute (RPI). We reside at the intersection of **Physics-Informed AI**, **Nonlinear Dynamics**, and **Autonomous Scientific Computing**.

[🌐 Lab Website](https://www.shaowupan.com) | [📧 Contact](mailto:span@rpi.edu) | [📍 RPI MANE](https://mane.rpi.edu/)

---

### 🧬 Our Core Research Pillars

- **Koopman Dynamics** `Koopman-Stable`  
  Stable embeddings for dynamics and control.  
  - **Phase I (2018)** `Long-Horizon + Jacobian Regularization`  
    - [Long-time predictive modeling of nonlinear dynamical systems using neural networks](https://arxiv.org/abs/1805.12547)  
  - **Phase II (2019–2020)** `Stability + Time Delay Embedding`  
    - [Physics-Informed Probabilistic Learning of Linear Embeddings of Non-linear Dynamics With Guaranteed Stability](https://arxiv.org/abs/1906.03663)  
    - [On the Structure of Time-delay Embedding in Linear Models of Non-linear Dynamical Systems](https://arxiv.org/abs/1902.05198)  
  - **Phase III (2021)** `Modes Selection`  
    - [Sparsity-promoting algorithms for the discovery of informative Koopman-invariant subspaces](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/sparsitypromoting-algorithms-for-the-discovery-of-informative-koopmaninvariant-subspaces/F52F03ED181023369A661EF09B57281A)  
  - **Phase IV (2024)** `Multi-Attractor + Open Source`  
    - [On the lifting and reconstruction of nonlinear systems with multiple invariant sets](https://link.springer.com/article/10.1007/s11071-024-09581-0)  
    - [PyKoopman: A Python Package for Data-Driven Approximation of the Koopman Operator](https://joss.theoj.org/papers/10.21105/joss.05881)  
  - **Phase V (2025)** `Noise-Robust Koopman and Control`  
    - [Learning Noise-Robust Stable Koopman Operator for Control With Hankel DMD](https://arxiv.org/abs/2408.06607)  

- **Neural Representations** `Operator Learning`  
  Mesh-agnostic neural fields and operator surrogates.  
  - **Phase I (2019)** `CNN Surrogates`  
    - [Prediction of Aerodynamic Flow Fields Using Convolutional Neural Networks](https://link.springer.com/article/10.1007/s00466-019-01740-0)  
  - **Phase II (2020)** `PINNs`  
    - [Surrogate Modeling for Fluid Flows Based on Physics-Constrained Deep Learning Without Simulation Data](https://arxiv.org/abs/1906.02382)  
    - [Stiff-PINN: Physics-Informed Neural Network for Stiff Chemical Kinetics](https://arxiv.org/abs/2011.04520)  
    - [Particle reconstruction of volumetric particle image velocimetry with strategy of machine learning](https://link.springer.com/article/10.1186/s42774-021-00087-6)  
  - **Phase III (2023)** `Bridging INR with Operator Learning`  
    - [Neural Implicit Flow: a mesh-agnostic dimensionality reduction paradigm of spatio-temporal data](https://arxiv.org/abs/2204.03216)  
  - **Phase IV (2024)** `Apply in Plasma`  
    - [Grad–Shafranov equilibria via data-free physics informed neural networks](https://arxiv.org/abs/2311.13491)  
  - **Phase V (2025–2026)** `Apply in Nuclear`  
    - [Surrogate modeling of heat transfer using Fourier Basis-DeepONet with uncertainty quantification](https://www.sciencedirect.com/science/article/abs/pii/S0149197025002938)  
    - [Characterization of DeepONet Performance for Neutron Transport Modeling](https://doi.org/10.1080/00295639.2025.2586955)  

- **CFD and ROMs**   
  Turbulence closures and high-rank reduced models.  
  - **Phase I (2014–2015)** `High-Speed CFD`  
    - [Numerical investigation of rarefaction effects in the vicinity of a sharp leading edge](https://pubs.aip.org/aip/acp/article-pdf/1628/1/185/11675955/185_1_online.pdf)  
    - [Combustion Heat-Release Effects on Supersonic Compressible Turbulent Boundary Layers](https://doi.org/10.2514/1.J053585)  
    - [An extended CFD model to predict the pumping curve in low pressure plasma etch chamber](https://pubs.aip.org/aip/acp/article-pdf/1628/1/1378/11675825/1378_1_online.pdf)  
  - **Phase II (2017)** `ML turbulence modeling`  
    - [Characterizing and improving predictive accuracy in shock-turbulent boundary layer interactions using data-driven models](https://doi.org/10.2514/6.2017-0314)  
    - [Augmentation of turbulence models using field inversion and machine learning](https://deepblue.lib.umich.edu/bitstream/handle/2027.42/143032/6.2017-0993.pdf?sequence=1)  
    - [The role of bulk viscosity on the decay of compressible, homogeneous, isotropic turbulence](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/role-of-bulk-viscosity-on-the-decay-of-compressible-homogeneous-isotropic-turbulence/96619135BA0A3ACB20EAC44ADF8261D1)  
  - **Phase III (2018)** `Data-Driven Closures`  
    - [Data-driven Discovery of Closure Models](https://arxiv.org/abs/1803.09318)  
  - **Phase IV (2025)** `A Near-Optimal Low-Rank Representation`  
    - [Beyond the Kolmogorov Barrier: A Learnable Weighted Hybrid Autoencoder for Model Order Reduction](https://arxiv.org/abs/2410.18148)  

- **Agentic CFD Automation** `Foam-Agent`  
  Agentic tools for OpenFOAM automation and data.  
  - **Phase I (2025)** `Agents for CFD`  
    - [Foam-Agent: Towards Automated Intelligent CFD Workflows](https://arxiv.org/abs/2505.04997)  
    - [FoamGPT: Fine-Tuning Large Language Model for Agentic Automation of CFD Simulations with OpenFOAM](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_271.pdf)  
  - **Phase II (2025)** `Ecosystems + Infrastructure in the era of LLMs`  
    - [Code2MCP: Transforming Code Repositories into MCP Services](https://arxiv.org/abs/2509.05941)  
    - [UniFoil: A Universal Dataset of Airfoils in Transitional and Turbulent Regimes](https://arxiv.org/abs/2505.21124)  


### 🛠 Tech Stack & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-5F33FF?style=for-the-badge&logo=google&logoColor=white)
![OpenFOAM](https://img.shields.io/badge/OpenFOAM-005A9C?style=for-the-badge&logo=openfoam&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 🌟 Featured Repositories

| Project | Description | Status |
| :--- | :--- | :--- |
| [**PyKoopman**](https://github.com/dynamicslab/pykoopman) | The premier Python library for Koopman operator learning. | ⭐ Active |
| [**Foam-Agent**](https://github.com/csml-rpi/foam-agent) | Agentic AI framework for automated OpenFOAM simulations. | 🚀 New |
| [**NIF**](https://github.com/pswpswpsw/nif) | Neural Implicit Flow for mesh-agnostic reduced-order modeling. | 📄 Paper |
| [**CFDLLMBench**](https://github.com/csml-rpi/cfd-llm-bench) | Benchmarking LLMs on Computational Fluid Dynamics tasks. | 📊 Research |

---

### 📈 Lab Repo Statistics
| ![Repos](https://img.shields.io/badge/Public_Projects-10+-blue?style=flat-square&logo=github) | ![Language](https://img.shields.io/badge/Primary_Stack-Python/JAX/PyTorch-green?style=flat-square) | ![Stars](https://img.shields.io/badge/Total_Stars-500+-yellow?style=flat-square&logo=github) |
| ![License](https://img.shields.io/badge/License-MIT/Apache-lightgrey?style=flat-square) | ![CI/CD](https://img.shields.io/badge/CI%2FCD-Passing-success?style=flat-square&logo=github-actions) | ![Contributors](https://img.shields.io/badge/Contributors-7_PHDs-orange?style=flat-square) |
---

### 🤝 Join Us
We are always looking for passionate Ph.D. students and postdocs interested in SciML and Agentic AI. 
- **Prospective Students:** Please check our [Application Guide](https://www.shaowupan.com/join-us).
- **Collaborations:** Open a discussion in any of our repos or reach out via email.

*"Simulating the future, one agent at a time."*

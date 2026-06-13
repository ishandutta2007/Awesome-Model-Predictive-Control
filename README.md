# Awesome-Model-Predictive-Control
## Top Model Predictive Control (MPC) Tools for Robotics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Model Predictive Control for Robotics, Locomotion & Autonomous Systems*  
**Last updated: March 2026**

This repository tracks notable **platforms** and **open-source projects** for **Model Predictive Control (MPC)** in robotics. These tools solve optimal control problems in real-time, enabling dynamic locomotion, manipulation, trajectory optimization, and constraint handling for legged robots, drones, arms, and autonomous vehicles.

**Examples** include zhm-real/MotionPlanning, NikolasEnt/Model-Predictive-Control, TinyMPC, CasADi, acados, and various distributed MPC toolboxes (the category leaders). Tools listed here emphasize **real-time performance**, constraint handling, nonlinear optimization, and integration with modern simulators.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local development, real-time deployment, and research reproducibility — ideal for robotics researchers, engineers, and developers building advanced control systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Proprietary / Commercial Tools](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Proprietary / Commercial Tools

### Comparison of Commercial MPC Solutions

| Product | Vendor | Company Size (Est. Revenue/Valuation) | Pricing (Commercial) | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Simatic PCS 7 MPC](https://www.siemens.com/global/en/products/automation/process-automation/distributed-control-system-simatic-pcs-7.html)** | Siemens | ~$84 Billion (Revenue) | €5,000+ (DCS Bundle) | No free tier; Demo/Quote only. |
| **[B&R Automation MPC](https://www.br-automation.com/en/products/software/automation-studio/)** | B&R (ABB) | ~$33 Billion (Revenue) | Subscription / Perpetual | **90-day fully functional trial.** |
| **[Pavilion8 / PavilionX](https://www.rockwellautomation.com/en-us/products/software/factorytalk/pavilion8.html)** | Rockwell | ~$8.3 Billion (Revenue) | ~$169,000+ (Enterprise) | No free tier; Demo/Quote only. |
| **[MATLAB MPC Toolbox](https://mathworks.com/products/model-predictive-control.html)** | MathWorks | ~$1.5 Billion (Revenue) | ~$1,180/year (Add-on) | 30-day full-featured free trial. |
| **[TwinCAT MPC](https://www.beckhoff.com/en-en/products/automation/twincat/tfxxxx-twincat-3-functions/tf5xxx-twincat-3-kinematics-and-robotics/tf5110.html)** | Beckhoff | ~$1.2 Billion (Revenue) | Hardware-dependent (TF511x) | **7-day renewable trial** (Indefinite testing). |
| **[dSPACE MPC Tools](https://dspace.com/)** | dSPACE | ~$480 Million (Revenue) | Custom Quote | No free tier; Academic discounts available. |
| **[FORCES Pro](https://www.embotech.com/products/forces-pro/overview/)** | Embotech | ~$200 Million (Valuation) | Subscription (Custom Quote) | **Free for Academic use** (Full features). |

### Core MPC Solutions Overview

- **MATLAB MPC Toolbox**  
  Industry-standard commercial toolbox with powerful design, simulation, and deployment capabilities. Widely used in academia and automotive/aerospace prototyping.

- **FORCES Pro (Embotech)**  
  High-performance embedded optimization solver that generates library-free C-code. Specifically optimized for fast real-time MPC in robotics and autonomous vehicles.

- **dSPACE MPC Tools**  
  Professional rapid control prototyping and MPC development environment. Often bundled with high-end HIL (Hardware-in-the-Loop) systems for automotive testing.

- **TwinCAT MPC (Beckhoff)**  
  Integrated MPC functionality within the TwinCAT 3 environment, allowing seamless control of industrial robot arms and high-speed machinery.

**Other notable mentions**: Siemens, Rockwell Automation, and various vendor-specific MPC modules for large-scale process optimization.

## Open-Source GitHub Projects

### Dedicated Model Predictive Control Projects

- **[zhm-real/MotionPlanning](https://github.com/zhm-real/MotionPlanning)** [![GitHub stars](https://img.shields.io/github/stars/zhm-real/MotionPlanning?style=social&color=white)](https://github.com/zhm-real/MotionPlanning/stargazers)  
  Open-source motion planning and MPC toolbox focused on robotics applications with practical implementations.

- **[CasADi](https://github.com/casadi/casadi)** [![GitHub stars](https://img.shields.io/github/stars/casadi/casadi?style=social&color=white)](https://github.com/casadi/casadi/stargazers)  
  Leading open-source symbolic framework for nonlinear optimization and optimal control. Widely used as the foundation for real-time MPC in robotics.

- **[OSQP](https://github.com/osqp/osqp)** [![GitHub stars](https://img.shields.io/github/stars/osqp/osqp?style=social&color=white)](https://github.com/osqp/osqp/stargazers)  
  Operator Splitting Quadratic Program solver — fast, reliable, and widely used in robotics MPC.

- **[acados](https://github.com/acados/acados)** [![GitHub stars](https://img.shields.io/github/stars/acados/acados?style=social&color=white)](https://github.com/acados/acados/stargazers)  
  High-performance, open-source framework for fast embedded optimization and MPC. Optimized for real-time applications on embedded hardware.

- **[TinyMPC](https://github.com/TinyMPC/TinyMPC)** [![GitHub stars](https://img.shields.io/github/stars/TinyMPC/TinyMPC?style=social&color=white)](https://github.com/TinyMPC/TinyMPC/stargazers)  
  Lightweight, high-speed MPC solver designed for resource-constrained robotic systems and embedded deployment.

- **[qpOASES](https://github.com/coin-or/qpOASES)** [![GitHub stars](https://img.shields.io/github/stars/coin-or/qpOASES?style=social&color=white)](https://github.com/coin-or/qpOASES/stargazers)  
  Reliable open-source quadratic programming solver extensively used in real-time MPC implementations.

- **[NikolasEnt/Model-Predictive-Control](https://github.com/NikolasEnt/Model-Predictive-Control)** [![GitHub stars](https://img.shields.io/github/stars/NikolasEnt/Model-Predictive-Control?style=social&color=white)](https://github.com/NikolasEnt/Model-Predictive-Control/stargazers)  
  Comprehensive open-source MPC library with clear examples for robotics and control systems.

- **[Crocoddyl](https://github.com/loco-3d/crocoddyl)** [![GitHub stars](https://img.shields.io/github/stars/loco-3d/crocoddyl?style=social&color=white)](https://github.com/loco-3d/crocoddyl/stargazers)  
  Optimal control library with excellent support for whole-body MPC and contact-rich robotics scenarios.

- **[sympy-to-numba/Model-Predictive-Controller](https://github.com/sympy-to-numba/Model-Predictive-Controller)** [![GitHub stars](https://img.shields.io/github/stars/sympy-to-numba/Model-Predictive-Controller?style=social&color=white)](https://github.com/sympy-to-numba/Model-Predictive-Controller/stargazers)  
  Open-source tool that converts symbolic MPC formulations (SymPy) to high-speed numerical code (Numba).

- **[dmpc - Distributed Model Predictive Control Toolbox](https://github.com/search?q=dmpc)**  
  Open-source toolbox for distributed MPC, ideal for multi-robot and large-scale systems.

### Additional Strong Open-Source Options

- **[Pinocchio](https://github.com/stack-of-tasks/pinocchio)** [![GitHub stars](https://img.shields.io/github/stars/stack-of-tasks/pinocchio?style=social&color=white)](https://github.com/stack-of-tasks/pinocchio/stargazers) — Rigid body dynamics library used as backend for many MPC stacks.
- **[Pink](https://github.com/stack-of-tasks/pink)** [![GitHub stars](https://img.shields.io/github/stars/stack-of-tasks/pink?style=social&color=white)](https://github.com/stack-of-tasks/pink/stargazers) — Inverse kinematics and whole-body control with MPC integration.
- **[RAI](https://github.com/search?q=robot+mpc)** — Various robotics MPC repositories built on CasADi and acados.
- **[Dynamic Matrix Control & EPFC Toolboxes](https://github.com/search?q=dmc+epfc)** — Open-source implementations of classic and advanced MPC algorithms.
- **[Learnable Fuzzy Gain-Scheduled PID + MPC Hybrids](https://github.com/search?q=fuzzy+mpc)** — Community projects combining classical and learning-based control.
- **Difference of Convex Neural Network Dynamic Approximation** implementations for advanced nonlinear MPC.

**Frameworks for building custom MPC systems**: Combine **CasADi** + **acados** + **Pinocchio** with **ROS2** and simulators (MuJoCo, Isaac Gym) for full-stack robotic MPC development.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- MPC performance on real robots requires careful tuning, safety layers, and extensive simulation testing before hardware deployment.
- Many solvers are sensitive to numerical conditioning — always validate stability.

---

**Made for robotics researchers, control engineers, and humanoid/autonomous system developers.**  
Let's make advanced Model Predictive Control more accessible, efficient, and open.
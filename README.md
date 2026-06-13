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

### Core MPC Solutions

- **[MATLAB MPC Toolbox](https://mathworks.com/products/model-predictive-control.html)**  
  Industry-standard commercial toolbox with powerful design, simulation, and deployment capabilities.

- **[dSPACE MPC Tools](https://dspace.com/)**  
  Professional rapid control prototyping and MPC development environment used in automotive and robotics.

**Other notable mentions**: Siemens, Rockwell Automation, and various vendor-specific MPC modules.

## Open-Source GitHub Projects

### Dedicated Model Predictive Control Projects

- **[CasADi](https://github.com/casadi/casadi)**  
  Leading open-source symbolic framework for nonlinear optimization and optimal control. Widely used as the foundation for real-time MPC in robotics.

- **[acados](https://github.com/acados/acados)**  
  High-performance, open-source framework for fast embedded optimization and MPC. Optimized for real-time applications on embedded hardware.

- **[TinyMPC](https://github.com/TinyMPC/TinyMPC)**  
  Lightweight, high-speed MPC solver designed for resource-constrained robotic systems and embedded deployment.

- **[zhm-real/MotionPlanning](https://github.com/zhm-real/MotionPlanning)**  
  Open-source motion planning and MPC toolbox focused on robotics applications with practical implementations.

- **[NikolasEnt/Model-Predictive-Control](https://github.com/NikolasEnt/Model-Predictive-Control)**  
  Comprehensive open-source MPC library with clear examples for robotics and control systems.

- **[dmpc - Distributed Model Predictive Control Toolbox](https://github.com/search?q=dmpc)**  
  Open-source toolbox for distributed MPC, ideal for multi-robot and large-scale systems.

- **[sympy-to-numba/Model-Predictive-Controller](https://github.com/sympy-to-numba/Model-Predictive-Controller)**  
  Open-source tool that converts symbolic MPC formulations (SymPy) to high-speed numerical code (Numba).

- **[qpOASES](https://github.com/coin-or/qpOASES)**  
  Reliable open-source quadratic programming solver extensively used in real-time MPC implementations.

- **[OSQP](https://github.com/osqp/osqp)**  
  Operator Splitting Quadratic Program solver — fast, reliable, and widely used in robotics MPC.

- **[Crocoddyl](https://github.com/loco-3d/crocoddyl)**  
  Optimal control library with excellent support for whole-body MPC and contact-rich robotics scenarios.

### Additional Strong Open-Source Options

- **[Pink](https://github.com/stack-of-tasks/pink)** — Inverse kinematics and whole-body control with MPC integration.
- **[Pinocchio](https://github.com/stack-of-tasks/pinocchio)** — Rigid body dynamics library used as backend for many MPC stacks.
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
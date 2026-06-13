<p align="center">
  <img src="assets/banner.svg" alt="Awesome MPC Banner" width="800">
</p>

<h1 align="center">🚀 Awesome Model Predictive Control (MPC)</h1>

<p align="center">
  <strong>A curated list of state-of-the-art Model Predictive Control (MPC) tools, solvers, and frameworks for Robotics, Autonomous Systems, and Industrial Automation.</strong>
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Model-Predictive-Control/stargazers"><img src="https://img.shields.io/github/stars/v88/Awesome-Model-Predictive-Control?style=for-the-badge&color=white" alt="Stars"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Model-Predictive-Control/network/members"><img src="https://img.shields.io/github/forks/v88/Awesome-Model-Predictive-Control?style=for-the-badge&color=white" alt="Forks"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Model-Predictive-Control/issues"><img src="https://img.shields.io/github/issues/v88/Awesome-Model-Predictive-Control?style=for-the-badge&color=white" alt="Issues"></a>
  <img src="https://img.shields.io/badge/Maintenance-Active-green?style=for-the-badge" alt="Maintenance">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow&style=for-the-badge" /></a>
</p>

---

## 📖 Overview

This repository is a comprehensive index of **Model Predictive Control (MPC)** resources. Whether you are working on **humanoid locomotion**, **autonomous vehicle trajectory planning**, or **industrial process control**, this list tracks the most reliable and high-performance tools in the ecosystem.

### Why MPC? 🧠
Model Predictive Control is the gold standard for handling complex constraints and multivariable dynamics in real-time. It allows robots to "look ahead" and optimize their behavior based on a predictive model of the environment.

---

## 📑 Table of Contents
- [🏢 Proprietary / Commercial Tools](#proprietary--commercial-tools)
- [🛠️ Open-Source GitHub Projects](#open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#disclaimer)

---

## 🏢 Proprietary / Commercial Tools

### Comparison of Commercial MPC Solutions 📊

| Product | Vendor | Company Size (Est. Revenue) | Pricing (Commercial) | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Simatic PCS 7 MPC](https://www.siemens.com/global/en/products/automation/process-automation/distributed-control-system-simatic-pcs-7.html)** | Siemens | ~$84 Billion | €5,000+ (DCS Bundle) | No free tier; Demo/Quote only. |
| **[B&R Automation MPC](https://www.br-automation.com/en/products/software/automation-studio/)** | B&R (ABB) | ~$33 Billion | Subscription / Perpetual | **90-day fully functional trial.** |
| **[Pavilion8 / PavilionX](https://www.rockwellautomation.com/en-us/products/software/factorytalk/pavilion8.html)** | Rockwell | ~$8.3 Billion | ~$169,000+ | No free tier; Demo/Quote only. |
| **[MATLAB MPC Toolbox](https://mathworks.com/products/model-predictive-control.html)** | MathWorks | ~$1.5 Billion | ~$1,180/year | 30-day full-featured trial. |
| **[TwinCAT MPC](https://www.beckhoff.com/en-en/products/automation/twincat/tfxxxx-twincat-3-functions/tf5xxx-twincat-3-kinematics-and-robotics/tf5110.html)** | Beckhoff | ~$1.2 Billion | Hardware-dependent | **7-day renewable trial.** |
| **[dSPACE MPC Tools](https://dspace.com/)** | dSPACE | ~$480 Million | Custom Quote | No free tier; Academic discounts. |
| **[FORCES Pro](https://www.embotech.com/products/forces-pro/overview/)** | Embotech | ~$200M (Val) | Subscription | **Free for Academic use.** |

### Core MPC Solutions Overview 🔍

- **MATLAB MPC Toolbox**  
  Industry-standard commercial toolbox for design and simulation. 🏎️ *Best for rapid prototyping.*
- **FORCES Pro (Embotech)**  
  High-performance embedded optimization. ⚡ *Best for real-time robotic deployment.*
- **dSPACE MPC Tools**  
  Professional rapid control prototyping. 🛠️ *Best for Automotive HIL testing.*
- **TwinCAT MPC (Beckhoff)**  
  Industrial PC-based control. 🏗️ *Best for high-speed manufacturing.*

---

## 🛠️ Open-Source GitHub Projects

### Dedicated Model Predictive Control Projects 🏎️

- **[zhm-real/MotionPlanning](https://github.com/zhm-real/MotionPlanning)** [![GitHub stars](https://img.shields.io/github/stars/zhm-real/MotionPlanning?style=social&color=white)](https://github.com/zhm-real/MotionPlanning/stargazers)  
  Motion planning & MPC toolbox focused on practical robotics implementations.

- **[CasADi](https://github.com/casadi/casadi)** [![GitHub stars](https://img.shields.io/github/stars/casadi/casadi?style=social&color=white)](https://github.com/casadi/casadi/stargazers)  
  The leading symbolic framework for nonlinear optimization. 🦴 *The backbone of modern MPC.*

- **[OSQP](https://github.com/osqp/osqp)** [![GitHub stars](https://img.shields.io/github/stars/osqp/osqp?style=social&color=white)](https://github.com/osqp/osqp/stargazers)  
  Fast Operator Splitting Quadratic Program solver. ⚡ *Ubiquitous in embedded robotics.*

- **[acados](https://github.com/acados/acados)** [![GitHub stars](https://img.shields.io/github/stars/acados/acados?style=social&color=white)](https://github.com/acados/acados/stargazers)  
  High-performance solver for fast embedded optimization. 🚀 *The choice for real-time performance.*

- **[TinyMPC](https://github.com/TinyMPC/TinyMPC)** [![GitHub stars](https://img.shields.io/github/stars/TinyMPC/TinyMPC?style=social&color=white)](https://github.com/TinyMPC/TinyMPC/stargazers)  
  Lightweight MPC for resource-constrained robotic systems. 🔋 *Perfect for micro-drones.*

- **[qpOASES](https://github.com/coin-or/qpOASES)** [![GitHub stars](https://img.shields.io/github/stars/coin-or/qpOASES?style=social&color=white)](https://github.com/coin-or/qpOASES/stargazers)  
  Reliable online active set strategy for QP. 🛡️ *Stable and field-proven.*

- **[NikolasEnt/Model-Predictive-Control](https://github.com/NikolasEnt/Model-Predictive-Control)** [![GitHub stars](https://img.shields.io/github/stars/NikolasEnt/Model-Predictive-Control?style=social&color=white)](https://github.com/NikolasEnt/Model-Predictive-Control/stargazers)  
  Comprehensive library with clear examples for robotics. 📚 *Great for learning MPC basics.*

- **[Crocoddyl](https://github.com/loco-3d/crocoddyl)** [![GitHub stars](https://img.shields.io/github/stars/loco-3d/crocoddyl?style=social&color=white)](https://github.com/loco-3d/crocoddyl/stargazers)  
  Optimal control library for whole-body MPC. 🤖 *Specialized for legged locomotion.*

- **[sympy-to-numba/Model-Predictive-Controller](https://github.com/sympy-to-numba/Model-Predictive-Controller)** [![GitHub stars](https://img.shields.io/github/stars/sympy-to-numba/Model-Predictive-Controller?style=social&color=white)](https://github.com/sympy-to-numba/Model-Predictive-Controller/stargazers)  
  Symbolic MPC formulations (SymPy) to high-speed Numba code. 🐍 *Python-friendly performance.*

### Additional Strong Open-Source Options 🧩

- **[Pinocchio](https://github.com/stack-of-tasks/pinocchio)** [![GitHub stars](https://img.shields.io/github/stars/stack-of-tasks/pinocchio?style=social&color=white)](https://github.com/stack-of-tasks/pinocchio/stargazers) — High-speed rigid body dynamics backend.
- **[Pink](https://github.com/stack-of-tasks/pink)** [![GitHub stars](https://img.shields.io/github/stars/stack-of-tasks/pink?style=social&color=white)](https://github.com/stack-of-tasks/pink/stargazers) — Inverse kinematics with MPC integration.

---

## 🤝 How to Contribute

We welcome contributions! 🌟
1. **Fork** the repository.
2. **Add/Edit** entries (follow the table/list style).
3. **Submit** a PR with a brief description of the tool.

---

## 📈 Star History

<div align="center">
   <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Model-Predictive-Control&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Model-Predictive-Control&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Model-Predictive-Control&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Model-Predictive-Control&type=date&legend=bottom-right" />
    </picture>
   </a>
</div>

---

## ⚠️ Disclaimer

- This is a **community-curated** list. Use these tools at your own risk.
- MPC stability on hardware depends heavily on model accuracy and solver tuning.
- Always validate in simulation (MuJoCo, Isaac Gym, Gazebo) before hardware tests.

---

<p align="center">
  <b>Built with ❤️ for the Robotics Community</b>
</p>
---
layout: page
title: Fractional-Order Dynamics
description: Numerical Simulation and Control of Frictional-order Dynamics
img: assets/img/Frac_Main.jpg
importance: 2
category: work
giscus_comments: true
---


This paper presents a novel approach for modeling and controlling multi-input multi-output (MIMO) fractional-order dynamic systems, which are increasingly used to describe complex physical behaviors more accurately than traditional integer-order models. We develop an analytical, discrete-time solution to systems of non-commensurate fractional-order differential equations using the Grünwald–Letnikov definition. This solution is specifically tailored for implementation on digital platforms by enabling finite-memory truncation, overcoming major limitations of continuous-time methods such as high computational cost and impractical memory demands. The approach provides clear truncation standards, making it practical for engineers without requiring deep expertise in fractional calculus.

Building on this foundation, the paper introduces an Enhanced Sliding Mode Control (ESMC) strategy that operates in discrete-time and effectively handles parameter uncertainties and external disturbances without resorting to fractional-order operators in the control law. The control scheme avoids chattering and is computationally efficient, making it suitable for real-world applications. We propose a novel method for solving the associated linear matrix inequalities and demonstrate the control strategy on a benchmark MIMO fractional-order system. The results showcase ESMC’s robustness and precision, providing a promising framework for controlling complex fractional systems using standard digital controllers. Further, we explore fractional-order actuation systems and how they can be connected to mechanical systems. The Model-Predictive Control (MPC) control of input-saturated fractional dynamics is also explored, and promising results are shown.

[1] Homaeinezhad, M. R., & Shahhosseini, A. (2020). Fractional order actuation systems: Theoretical foundation and application in feedback control of mechanical systems. Applied Mathematical Modelling, 87, 625-639.

[2] Homaeinezhad, M. R., & Shahhosseini, A. (2020). High-performance modeling and discrete-time sliding mode control of uncertain non-commensurate linear time invariant MIMO fractional order dynamic systems. Communications in Nonlinear Science and Numerical Simulation, 84, 105200.

[3] Homaeinezhad, M. R., & Shahhosseini, A. (2021). Parameter-disturbance-robust model predictive control of input-saturated MIMO fractional systems. International Journal of Dynamics and Control, 9(3), 1117-1131.

---
layout: page
title: Simulation of Piecewise Linear Systems
description: A Hybrid Symbolic-Numeric Computational tool was developed
img: assets/img/Main_HSNC.jpg
importance: 1
category: work
related_publications: true
---


This paper presents a computational framework for analyzing mechanical systems that exhibit complex nonlinear behavior due to friction and intermittent contact, features common in real-world assemblies such as cracked structures, loose joints, and frictional interfaces. These systems are modeled using a class known as piecewise linear systems with discontinuous force elements (PWLDFE), capable of reproducing a rich variety of motions, including periodic, chaotic, and the rarely observed weakly chaotic dynamics. The proposed modeling formalism leverages the theory of differential inclusions to rigorously handle these discontinuities, offering both physical insight and mathematical generality.



<div class="row justify-content-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid 
            loading="eager" 
            path="assets/img/HSNC_P1.png" 
            title="HSNC in action" 
            class="img-fluid rounded z-depth-1" 
        %}
    </div>
</div>


To make the analysis of such systems practical, we develop a hybrid symbolic-numeric computational (HSNC) method that significantly outperforms conventional numerical integration in both speed and accuracy. The method constructs exact analytical solutions between dynamical switches and efficiently detects those switches to piece together a complete system response. It is applicable to high-dimensional models without requiring model reduction and is particularly suited for cases where transient or non-steady dynamics are of interest. Demonstrations include not only conventional scenarios but also systems exhibiting weak chaos, where the divergence of trajectories is non-exponential—a subtle but important behavior in the study of nonlinear dynamics.




[1] Shahhosseini, A., Tien, M. H., & D'Souza, K. (2023). Efficient hybrid symbolic-numeric computational method for piecewise linear systems with Coulomb friction. Journal of Computational and Nonlinear Dynamics, 18(7), 071004.

[2] Shahhosseini, A., & D’Souza, K. (2023, June). Abstract Dynamics: An Alternative Approach to Local Lyapunov Exponents in Examining Local Unpredictability. In International Conference on Nonlinear Dynamics and Applications (pp. 305-315). Cham: Springer Nature Switzerland.

[3] Shahhosseini, A., Tien, M. H., & D’Souza, K. (2021, August). Analysis and Evaluation of Piecewise Linear Systems With Coulomb Friction Using a Hybrid Symbolic-Numeric Computational Method. In International Design Engineering Technical Conferences and Computers and Information in Engineering Conference (Vol. 85468, p. V009T09A009). American Society of Mechanical Engineers.

---
layout: default
icon: fea.gif
title: Finite Element Analysis
description: Matlab Code to approximate 2nd order Partial Differential Heat Equation
---
<a href="https://github.com/whashi44/MatlabFEA" target="_blank" title="Github">
        <i class="fab fa-github fa-2x " style="color:black"> Code</i>
    </a>

# Summary
<img src="/assets/images/portfolio/fea.gif" alt="FEA Gif">

This is a matlab code for the approximation of following 2nd order partial differential equation:

<div>\[\frac{\partial p}{\partial t} - \nabla\cdot(\bf{K}\nabla p) = q\]</div>

by converting the strong form to weak form using divergent theorem, and approximating the solution using discretization, shape function, Gallerkin's approximation, and Gaussian quadrature. The resulting animation is below, whichshows the approximate solution beingupdated every time step to obtain theoretical solution. <br>

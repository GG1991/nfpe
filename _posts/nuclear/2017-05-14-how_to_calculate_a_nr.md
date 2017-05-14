---
title: How To Calculate a Nuclear Reactor   
category: Nuclear
author: Guido Giuntoli
use_math: true
feature_image: "https://unsplash.it/1200/400?image=200"
---

It was on Dicember 2, of 1942 when Fermi and a group of scientist controlled the first nuclear chain reaction. The
Manhattan project was running and scientific progress was fastly being developed.

{% include figure.html image="/assets/simu/nuclear/fuel_1.jpg" position="center" %}

The neutron diffusion equation can be written as:

$$
   |\psi_1\rangle = a|0\rangle + b|1\rangle
$$

\begin{equation}
\frac{1}{\nu_{g}}\frac{\partial \phi_{g}}{\partial t}  = D_{g} \nabla^{2} \phi_{g} 
-\sigma_{g}^{r} \phi_{g} + \sum_{g\prime\neq g} \sigma_{g'\rightarrow g }^{r}   \phi_{g\prime}+ (1-\beta)\sum_{g\prime} \chi_{g}\nu\sigma_{g'}^{f} 
\end{equation}

[comment]: <>+ \sum_{i=1}^{I} \chi_{g,i}\lambda_{i} C_{i}

\begin{equation}
\frac{\partial C_{i}}{\partial t}   = \sum_{g\prime}\beta_{i} \nu \sigma_{g'}^{f} \phi_{g\prime} - \lambda_{i} C_{i}
\end{equation}

#

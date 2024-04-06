This repository contains some of the notebooks written during the course of "Galaxies and Dynamics" (A.A. 2022/2023) of the Astrophysics and Space Physics master degree offered by the University of Milano-Bicocca.

For the N-body simulations, all notebooks use Barnes' tree-code: https://legacy.ifa.hawaii.edu/faculty/barnes/treecode/treeguide.html

Brief description of notebook contents:

Sphere: Initialization of a truncated sphere and simulation of collapse under self-gravity. Analysis of the collapse time and comparison with the analytic solution.

Plummer equilibrium: Initialization of a Plummer sphere in equilibrium using Monte-Carlo rejection method for the velocity distribution. Simulation of the evolution of the distribution and analysis of its equilibrium after few dynamical times.

Center of mass: Algorithm to compute the center of mass of a distribution using the shrinking sphere method. Comparison with pynbody function. Example using a Plummer sphere with analysis of equilibrium.

Hernquist_bh: Initialization of a Hernquist distribution with a central black hole in equilibrium, computing numerically the distribution function. Simulation of the evolution of the distribution and analysis of its equilibrium.

DyF_withEnergies: Initialization of a Plummer sphere with the addition of a perturber. Simulation and analysis of the evolution of the system due to the dynamical friction of the perturber.

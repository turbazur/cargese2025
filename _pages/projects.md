---
permalink: /projects/
title: "List of (prospective) Projects"
author_profile: true
---

(The list is purely indicative at this point)
1. **FRG fixed points of the 1D Burgers equation for randomly stirred fluids.** (LC) The project aims to derive the FRG flow equations for the 1D stochastic Burgers equation in a simple approximation, integrate numerically these equations to find the fixed point structure of the 1D Burgers equation and analyse the different scaling regimes.


1. **Lagrangian intermittency and irreversibility**  (MC)
I can use a small DB of Lagrangian trajectories to do some analysis of
Lagrangian structure functions and or Lagrangian power to discuss
irreversibility.
Eventually, the students can also do some conditional statistics. For
more motivated students I can also propose to do some simulations with
the shell model in its Lagrangian version. For the latter I can
provide a working C code.
 
1. **Anomalous scaling in passive scalars** (MC)
I can provide some fields of 2D scalar fields in 2D turbulence in the
inverse cascade and suggest some data analysis, such as structure
functions or analysis of the multipliers. 


1. **Spontaneous stochasticity of the Kuramoto-Sivashinsky equation**  (ES)

1. **Two-Point Statistics from Fiber Tracking Velocimetry in a turbulent channel flow** (CB)
This project aims at evaluating two-point statistics of a turbulent channel flow using rigid fibers transported by the flow. This technique, recently validated experimentally and numerically in homogeneous isotropic turbulence (Brizzolara et al., PRX, 2021), allows to measure flow transverse velocity increments and even the local turbulent dissipation rate for sufficiently short fibers. Using numerical data, we will apply this technique to a turbulent channel flow, which is inhomogenous and anisotropic. The length and inertia of the fibers will be varied to quantify the effect of these parameters on the measurements.

1. **Dynamical models for the turbulent cascade** (JB)
This project explores simplified dynamical models for the turbulent energy cascade that go beyond phenomenological approaches. The aim is to understand how intermittency, as described by Kolmogorov's 1962 refined self-similarity hypothesis, emerges dynamically from the coupling between scales. Students will construct and analyze stochastic evolution equations for coarse-grained energy transfers, investigating how fluctuations at small scales lead to intermittent statistics. A central aspect is to illustrate Eulerian spontaneous stochasticity, viewed through the lens of renormalization-group ideas, where multiplicative randomness arises from unresolved interactions. Model predictions will be compared with direct numerical simulations, focusing on scaling exponents, intermittency corrections, and the validity of refined similarity across scales.

1. **Spontaneous stochasticity in Reversible Navier-Stokes** (BD)
The spontaneous stochasticity is another name for the *butterfly effect* [L69,P14], first conjectured by Ed Lorenz in 1969. It results in an absolute finite time predictability barrier for turbulence or weather forecasting, which is independent of initial errors. In his original paper, Ed Lorenz believed that this predictability barrier was due to the multi-scale nature of the atmosphere.
Since then, this conjecture has been tested on many toy models of turbulence, such as dynamical system [MR23], shell models[M16,B24], Kraichnan model[F01] or Burgers equations[ED15]and in turbulent velocity fields[Th20]. These studies highlighted that another crucial ingredient to observe such effect was the singular nature of the velocity field. To date, it is however not clear whether the nature of the singularity influences the development of the spontaneous stochasticity. In this project, we aim at studying the influence of the dissipative nature of the singularity in a controlled system: the Reversible Navier-Stokes on Log-Lattice. Such system was shown to exhibit a wide variety of finite time blow-ups [C25], some of them being dissipative.
The log-lattice code is already available for the study and works on PCs. Numerical cost involved in this kind of simulations is rather mild, so this topic should rather be viewed as theoretical with light numerics.

1. **Zero-modes in a multifractal random shell model for scalar transport** (ST)
The project aims to analyse numerically and theoretically the emergence of non-Gaussian flatness in multifractal extension of random dyadic model, which can be seen as a shell model version of the Kraichnan model of scalar transport.

1. **Predictability of singular initial vorticity problems** (ST)
The goal of this project is to numerically  investigate examples of simple singular initial data  for which the 2D Euler equations or their variants,  have non-unique solutions.
One example is the 2D Kelvin-Helmoltz instability. When perturbed by a small noise it is known to give rise to spontaneous stochasticity of vortex sheets. The goal is to numerically investigate the universality of this mechanism when varying the range of interactions between the vortices. 
A second and perhaps simpler case is the initial data proposed by Bressan and Shen, 2019 (arxiv 2002.01962) where   vorticity has a point singularity.


1. **Eulerian two-points statistics and assessment of the Kolmogorov-Obohukov scale-similarity hypothesis ** (RZ)
This project is mainly a tutorial designed to let the students get familiarized with the basic concepts of turbulent field analysis (pdf, two-point correlation, structure function, etc.). By providing cross-sections from numerical simulations at Re_lambda = 350, students will be able to test Kolmogorov's K41 theory and its refined version, K62. Matlab and Python scripts are available, as well as a Jupiter notebook, at this address: 
[(https://gitlab.com/some_stuffs/tuto_turbulence](https://gitlab.com/some_stuffs/tuto_turbulence)


1. **Stochastic modeling of fluid tracers and time reversibility** (RZ)
A stochastic model describing the interactions of a fluid particle with all other fluid particles of a turbulent flow has been proposed based on a local relationship between the force on the fluid particle, kinetic energy and dissipation. This model exhibits some of the remarkable characteristics of fluid particle dynamics, in particular the occurrence of extreme events and the emergence of an anomalous scaling law. This model can also produce an asymmetry in certain statistics (such as the rate of kinetic energy variation) through time reversal, a sign of dissipative dynamics. This project aims to characterize and analyze the conditions under which such temporal asymmetry is possible and to identify the minimum ingredients to be incorporated into a stochastic model in order to obtain this behavior. In particular, initial empirical tests seem to show that it is necessary to have non-Markovian dynamics and a non-diagonal diffusion tensor. Python or C++ programs for simulating this stochastic process are available.


1. **Spectral periodicity** (RZ)
To represent an unbounded domain in a simulation, one generally applies periodic boundary conditions. This allows for translation invariance.  Of course, finite size effects remain, the largest structures cannot exceed the size of the domain.
Can periodic boundary conditions be applied in the spectral domain to simulate flow at infinite Reynolds number?
The idea of the project is to simulate Euler's equations in the spectral domain by applying periodicity in scale. These developments could capitalize on the log-lattice technique.  
This approach should, in principle, provide scale invariance, but there can be no interactions between modes of very different amplitudes, as the number of modes simulated remains finite.
To what extent could this type of approach represent an infinite Reynolds flow?  In particular, with regard to the intermittency effects?

---
permalink: /
title: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello!
I am a postdoctoral research scientist at the University of Waterloo.
My work falls into several areas, including
high performance computing,
machine learning,
quantum chemistry,
many-body physics,
and quantum computing.
My research interests are aimed at
using numerical methods
to perform classical simulations of quantum systems.

I earned my PhD from the University of Waterloo in September 2024,
where I was supervised by [Dr. Pierre Nicholas-Roy](https://uwaterloo.ca/chemistry/profile/pnroy).
My research focused on performing quantum Monte Carlo simulations of solid parahydrogen
using *ab initio* non-additive many-body potentials.
I would calculate the interaction energies between groups of hydrogen molecules
across thousands of jobs at once
on HPC supercomputer clusters provided by ComputeCanada.
Next I would use PyTorch to train neural networks that
predict the many-body interaction energies for these hydrogen molecules.
I would then perform path-integral Monte Carlo simulations of solid parahydrogen
using these many-body potentials.
The simulation code is written in modern C++20,
and the aforementioned neural networks were ported into C++ using LibTorch.

My current research is focused on quantum computing.
I'm performing Quantum Phase Estimation
and Variational Quantum Eigensolver simulations
for linear chains of dipolar planar rotors.

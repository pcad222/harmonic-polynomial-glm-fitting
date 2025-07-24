# harmonic-polynomial-glm-fitting

This repository contains code for fitting magnetic field data (Bx, By, Bz) using harmonic polynomial basis functions via generalized linear model (GLM) least-squares fitting.

## Features
- Builds harmonic polynomial basis functions up to degree `l_max`
- Fits all three magnetic field components simultaneously
- Supports Bx, By, Bz data in Cartesian coordinates

## Uses:
- The fitted G lm coefficients can be used to reconstruct the magnetic field at any location using the same harmonic basis

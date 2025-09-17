# ProjetMMC — LQR Control Around a Halo Orbit

**Author:** Bruno Gisbert  
**Contact:** brunogisbert@gmail.com · https://github.com/BrunoGisbert

## Overview
This repository implements an LQR controller to stabilize a Halo orbit around a Lagrange point. It contains scripts to compute a periodic orbit (differential correction), propagate the State Transition Matrix (STM), compute LQR gains, simulate closed-loop behavior, and analyze stability (monodromy).

## Features
- Find a periodic Halo orbit via differential correction.
- Linearize the dynamics along the trajectory and propagate the STM.
- Compute LQR gains and simulate closed-loop dynamics.
- Estimate Δv and analyze stability using the monodromy matrix.
- Notebooks for interactive visualization and analysis.

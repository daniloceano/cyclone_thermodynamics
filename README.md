

# ATMOS-BUD Overview

[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
![Documentation Status](https://readthedocs.org/projects/atmos-bud//badge/?version=latest)
![License](https://img.shields.io/github/license/daniloceano/ATMOS-BUD)

<img src="docs/_static/images/logo.jpg" alt="ATMOS-BUD Logo" width="200"/>

ATMOS-BUD is a comprehensive software suite designed for calculating heat, vorticity, and moisture balances within limited areas of the atmosphere. Developed at the Institute of Astronomy, Geophysics, and Atmospheric Sciences of the University of São Paulo, it's a key tool for students and researchers in atmospheric sciences.

### Key Features

- Processes atmospheric model and reanalysis data in NetCDF format.
- Outputs CSV files for spatial averages and a comprehensive NetCDF file for spatial results.
- Supports Fixed Domain, Semi-Lagrangian Domain, and Interactive Domain operational frameworks.

### Quasi-Geostrophic Thermodynamic Equation

```plaintext
∂T/∂t = -Vh · ∇hT - Σω + Q
```
*Where T is temperature, Vh is the horizontal wind vector, Σ is the static stability parameter, ω is the vertical velocity, and Q represents diabatic heating.*

### Quasi-Geostrophic Vorticity Budget Equation

```plaintext
∂ζ/∂t = -Vh · ∇hζ - (ζω/Δp) - βv - ζ∇ · Vh - f∇ · Vh + Tilting Term
```
*Where ζ is vorticity, β is the change in Coriolis parameter with latitude, and f is the Coriolis parameter.*

### Water Budget Equation

```plaintext
∫∂q/∂t dp = -∫Vh · ∇q dp + ∫S dp
```
*Where q is specific humidity, Vh is the horizontal wind vector, and S represents net sources/sinks.*

ATMOS-BUD combines academic rigor with practical application, making it a gateway to understanding atmospheric dynamics for both educational exploration and advanced research.

### Full Documentation

The full documentation for ATMOS-BUD can be found on [Read the Docs](https://atmos-bud.readthedocs.io).


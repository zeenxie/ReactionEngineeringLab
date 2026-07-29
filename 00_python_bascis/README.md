# 00_python_foundation

This module is the Python foundation layer of ReactionEngineeringLab.  
It is designed for chemical reaction engineering students who want to learn the scientific Python tools needed for reactor modeling, kinetics analysis, numerical solving, and data fitting.

The goal of this module is not to teach general-purpose programming.  
Instead, it focuses on Python skills that are directly useful in reaction engineering.

## Learning Goals

After completing this module, you should be able to:

- use NumPy to represent reaction engineering data such as time, concentration, conversion, and rate
- use Matplotlib to visualize reaction profiles and experimental data
- use SciPy to solve ordinary differential equations for reactor models
- fit kinetic parameters from experimental data
- prepare for the reactor design, kinetics, bioreactor, catalysis, and RTD modules

## Contents

### 01_numpy_for_reaction_engineering.ipynb
Learn how to use NumPy for reaction engineering data, vectorized calculations, and basic stoichiometric relationships.

### 02_plotting_reaction_profiles.ipynb
Learn how to plot concentration-time curves, conversion curves, rate curves, and Arrhenius plots.

### 03_solving_odes_with_scipy.ipynb
Learn how to solve ordinary differential equations with `scipy.integrate.solve_ivp` for batch reactors, CSTRs, and related dynamic models.

### 04_parameter_fitting.ipynb
Learn how to estimate kinetic parameters from experimental data using SciPy optimization tools.

## Recommended Order

1. `01_numpy_for_reaction_engineering.ipynb`
2. `02_plotting_reaction_profiles.ipynb`
3. `03_solving_odes_with_scipy.ipynb`
4. `04_parameter_fitting.ipynb`

## Dependencies

This module mainly uses:

- numpy
- scipy
- matplotlib
- pandas
- jupyter
- sympy

## How to Run

Activate the project environment first:

```bash
conda activate reactionlab
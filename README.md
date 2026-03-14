# Minor-research-project-
CFD analysis of mass transfer in micro-obstructed laminar channels using COMSOL

## Overview
This project investigates the effect of micro-obstructions on mass transfer in a laminar channel flow using CFD simulations in COMSOL Multiphysics.

The study focuses on how obstruction height ratio (h/H) influences the Sherwood number and mass transfer characteristics across different Peclet and Reynolds numbers.

## Objectives

- Simulate laminar flow and species transport in a 2D channel.
- Introduce micro-obstructions with varying height ratios (h/H).
- Evaluate mass transfer using the Sherwood number.
- Compare smooth channel vs obstructed channel performance.
- Analyze scaling relationship between Sherwood and Peclet numbers.

  ## Methodology

The simulations were performed using COMSOL Multiphysics.

### Physics Models
- Laminar Flow (Navier–Stokes)
- Transport of Diluted Species

### Parametric Study
The inlet velocity was varied to generate a range of Reynolds and Peclet numbers.

Obstruction height ratios analyzed:

- h/H = 0.1
- h/H = 0.2
- h/H = 0.3
- h/H = 0.4

### Performance Metrics

Sherwood number:

Sh = kL / D

Mass transfer enhancement:

Sh / Sh₀


## Results

The following analyses were performed:

- Sherwood number vs Peclet number
- Sherwood number vs Reynolds number
- Mass transfer enhancement (Sh/Sh₀)
- Log-log Sherwood scaling

Key observation:

Increasing obstruction height reduced mass transfer in the current configuration due to diffusion pathway blockage and formation of stagnant zones behind the obstacles.

## Repository Structure

data/
    without_obs.txt
    mrp_withobs.txt

analysis/
    plot_analysis.ipynb

figures/
    sherwood_vs_peclet.png
    sherwood_vs_reynolds.png
    enhancement.png


## Tools and Software

- COMSOL Multiphysics
- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab
  

## Author

Ankit Kumar  
B.Tech Chemical Engineering  
NIT Warangal

# Monte Carlo Simulation for Exotic Option Pricing (Asian Options)

## Overview

This project showcases a Python-based Monte Carlo simulation engine specifically designed to price path-dependent exotic options, with a particular focus on Asian options. Unlike European options, Asian options lack closed-form analytical solutions under the Black-Scholes framework, making numerical methods essential for accurate pricing.

## Objectives

* Develop a robust simulation framework using Geometric Brownian Motion (GBM).
* Accurately price Asian options through extensive simulations.
* Validate simulation accuracy by benchmarking against the Black-Scholes formula for European call options.

## Features

* **Geometric Brownian Motion (GBM)**: Models realistic asset price dynamics.
* **Asian Option Pricing**: Implements arithmetic averaging method for payoff calculations.
* **Statistical Validation**: Provides confidence intervals and accuracy metrics.
* **Visualization**: Offers clear graphical insights into simulated asset paths.

## Technical Details

* **Language**: Python
* **Libraries**: NumPy, SciPy, Matplotlib
* **Simulations**: 100,000 paths
* **Validation**: Compared against Black-Scholes analytical solutions (accuracy within 0.5%).

## Results

The Monte Carlo simulation demonstrated high precision and robustness, as evidenced by:

* Narrow confidence intervals indicating strong convergence.
* Validation results closely aligned with the analytical Black-Scholes benchmark, achieving discrepancies below 0.5%.

## Usage

Run the provided Jupyter notebook (`Monte_Carlo_Option_Pricing.ipynb`) to replicate the results, visualize asset price paths, and explore the underlying methodology.

```bash
git clone <https://github.com/hameed-abiodun/Monte-Carlo-Option-Pricing/>
jupyter notebook Monte_Carlo_Simulation.ipynb
```

## Potential Applications

* Risk management and derivatives pricing in financial institutions.
* Quantitative research and financial modeling.
* Portfolio hedging and strategic trading decisions.

## Author

* **\[Hameed Jimoh]**
* **Quantitative Analyst | Financial Engineer**
* [GitHub Profile](https://github.com/hameed-abiodun/)

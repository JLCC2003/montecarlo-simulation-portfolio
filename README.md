# Monte Carlo Simulation for Portfolio Modeling

## Overview

This project implements a **Monte Carlo simulation framework** in Python to model portfolio behavior under uncertainty. It simulates stochastic price paths and analyzes return distributions to evaluate financial risk and probabilistic outcomes.

The objective is to demonstrate practical implementation of quantitative finance methods using numerical techniques and stochastic modeling.

---

## Key Features

* Simulation of stochastic processes for asset price paths
* Portfolio return distribution analysis
* Risk estimation using probabilistic metrics
* Visualization of simulation outcomes
* Reproducible quantitative experiments in Jupyter Notebook

---

## Methodology

The model uses Monte Carlo simulation to generate multiple possible trajectories of asset returns. Each simulation represents a possible future scenario under stochastic dynamics.

Typical workflow:

1. Define model parameters (initial value, volatility, time horizon, iterations)
2. Generate random paths using pseudo-random sampling
3. Compute portfolio returns for each path
4. Analyze distribution statistics
5. Visualize results

---

## Mathematical Foundation

The simulations are based on stochastic processes commonly used in quantitative finance:

* Brownian Motion
* Geometric Brownian Motion (GBM)
* Random sampling methods
* Numerical approximations

---

## Tech Stack

* Python
* NumPy
* pandas
* matplotlib
* statistics
* random

---

## Example Outputs

Typical outputs produced by the simulation:

* Distribution of simulated returns
* Histogram of outcomes
* Simulated price trajectories
* Risk percentiles

---

## How to Run

Clone the repository and run the notebook:

```bash
git clone https://github.com/JLCC2003/montecarlo-simulation-portfolio.git
cd montecarlo-simulation-portfolio
jupyter notebook
```

---

## Applications

This framework can be extended for:

* Value at Risk (VaR) estimation
* Portfolio optimization studies
* Stress testing scenarios
* Option pricing simulations
* Risk management research

---

## Author

**Jairo Leonel Castro Cruz**
Mathematical Engineering Student — Quantitative Finance & Stochastic Modeling

---

## Project Status

Actively improving and expanding with additional models and risk metrics.

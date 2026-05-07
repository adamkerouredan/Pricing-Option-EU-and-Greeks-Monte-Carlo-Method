# European Option Pricing under Black-Scholes

This repository implements and compares classical numerical methods for pricing European options under the Black-Scholes framework.

The project covers Monte Carlo simulation, variance reduction techniques, finite difference schemes for the Black-Scholes PDE, and numerical estimation of option Greeks.

## Project Objectives

- Price European call and put options under the Black-Scholes model.
- Compare Monte Carlo estimates with closed-form Black-Scholes prices.
- Implement variance reduction techniques such as antithetic variables and control variates.
- Solve the Black-Scholes PDE using finite difference methods.
- Estimate and interpret the main option Greeks: Delta, Gamma, Vega, Theta and Rho.
- Study convergence, numerical error and confidence intervals.

## Methods Implemented

### Monte Carlo Simulation

- Standard Monte Carlo estimator
- Antithetic variables
- Control variates
- Empirical standard error estimation
- 95% confidence intervals
- Convergence analysis against Black-Scholes closed-form prices

### Finite Difference Methods

- Explicit finite difference scheme
- Implicit finite difference scheme
- Crank-Nicolson scheme
- Boundary conditions
- Stability and convergence analysis

### Greeks Estimation

The project studies the numerical estimation of:

- Delta
- Gamma
- Vega
- Theta
- Rho

The sensitivities are compared with the theoretical behaviour expected under the Black-Scholes framework.

## Numerical Report

A detailed PDF report is included in the repository.

It presents the mathematical background, the Black-Scholes model, Monte Carlo pricing, finite difference methods, variance reduction techniques, Greeks estimation and numerical results.

## Repository Content

├── README.md
├── finite_difference_methods.py
├── pricing_option_eu_and_greeks_monte_carlo_mathod.py
└── European_Option_Pricing_using_Monte_Carlo_Simulation_and_Finite_Difference_Methods.pdf




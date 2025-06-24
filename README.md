# Pricing-Option-EU-and-Greeks-Monte-Carlo-Method
# European Option Pricing – Monte Carlo & Finite Difference Methods (C++)

This project implements and compares two major numerical techniques for pricing European options under the Black-Scholes framework: Monte Carlo simulation and Finite Difference Methods (FDM). Written in C++ with performance and clarity in mind, the codebase provides a comprehensive exploration of option pricing and sensitivity analysis.

---

## Project Objectives

- Implement standard and variance-reduction Monte Carlo methods for European calls and puts.
- Develop explicit, implicit, and Crank-Nicolson schemes to solve the Black-Scholes PDE via finite differences.
- Compare accuracy, convergence, and computational cost of both approaches.
- Compute and interpret option Greeks: Delta, Gamma, Theta, Vega, and Rho.
- Provide a robust and documented pricing engine suitable for educational and pre-industrial use.

---

## Numerical Methods Implemented

### Monte Carlo Simulations
- Plain Monte Carlo estimator
- Antithetic variables
- Control variates (using closed-form Black-Scholes as control)
- Empirical estimation of convergence rate \(\mathcal{O}(1/\sqrt{N})\)
- Confidence intervals, standard errors, and error plots

### Finite Difference Methods
- Explicit (Forward Euler)
- Implicit (Backward Euler)
- Crank-Nicolson (θ-scheme)
- Stability conditions, boundary conditions, and convergence analysis
- Handling of payoff discontinuities (e.g., for put options)

---

## Greeks Calculation

For each method, sensitivity analysis is conducted:
- **Delta & Gamma**: via central finite differences
- **Theta**: backward difference in time
- **Vega & Rho**: forward sensitivity to volatility and interest rate
- Monte Carlo estimates use path-wise differentials with numerical approximations

---

## Key Features

- Fully commented and modular C++ implementation
- LaTeX-formatted report included (100+ pages, rigorous)
- Convergence analysis and error visualization
- Comparison to closed-form Black-Scholes prices for validation
- PDF and code structured for both academic and professional readers

---

## Outputs

- Graphical comparison of estimated vs exact prices
- Convergence of errors for each scheme
- Greeks vs underlying price curves
- Execution time benchmarks
- Option value surfaces (FDM)

---

## Requirements

- C++11 or higher
- G++ / Clang compiler
- Python 3 (for plotting output if needed)
- Optional: LaTeX (to compile the full report)




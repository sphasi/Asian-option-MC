# Pricing Asian Options: Replication of Research Papers

This repository contains materials from my project on pricing Asian options, completed as part of the **Monte Carlo for Finance** course at Paris-Dauphine University (Master MASEF). The project involves replicating the methodologies described in two research papers and applying both Monte Carlo and finite difference methods to estimate Asian option prices.

## Table of Contents
- [Project Overview](#project-overview)
- [Repository Contents](#repository-contents)
- [Prerequisites and Dependencies](#prerequisites-and-dependencies)
- [How to Run the Code](#how-to-run-the-code)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Project Overview

Asian options are a type of financial derivative whose payoff depends on the average price of the underlying asset over a specific period. Unlike standard options, pricing Asian options is more complex, often requiring advanced numerical techniques.

### Objectives
1. **Replicate Research Papers**: 
   - Study the schemes presented by Lapeyre and Temam (Monte Carlo approach).
   - Apply the finite difference method to solve the PDE described by Rogers and Shi.
2. **Methods Used**:
   - Monte Carlo simulations with three approximation schemes: Riemann, trapezoidal, and Black-Scholes.
   - PDE solution using an implicit Crank-Nicholson finite difference scheme.

### Key Results
The methods provide accurate pricing for Asian options under different volatilities, with notable efficiency improvements from variance reduction techniques. Moreover, the results obtained with the second paper seems more accurate, but the drawback is that the algorithm is slower.

## Repository Contents

1. **Slides**:
   - `PresMCfinal.pdf`: Summary of the project, including objectives, methods, and results. Used as a support to present my results.

2. **Report**:
   - `RapportAsianOption.pdf`: Detailed report covering the theoretical background, methods, and numerical results.

3. **Code**:
   - `MonteCarloScheme_AsianOption.ipynb`: Jupyter Notebook implementing the Monte Carlo methods with the Riemann, trapezoidal, and Black-Scholes schemes for Asian option pricing. This notebook also includes variance reduction techniques and numerical results.
   - `Finite_diff_method_AsianOption.ipynb`: Jupyter Notebook implementing the Finite difference method for solving the PDE described by Rogers and Shi.




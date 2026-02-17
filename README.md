# Advance-Mathematics
# Course: UCS654 -- Predictive Analytics using Statistics  
## Assignment: Assignment-3  
**Author:** Ishika Gupta
**Roll Number:** 102303460 

---

## About the Project
This project implements a roll-number-parameterized nonlinear transformation model to learn the parameters of a probability density function using real environmental air-quality data. The study uses **NO₂ (Nitrogen Dioxide)** concentration values from the India Air Quality Dataset and estimates the parameters of a Gaussian-type probability density function after applying a nonlinear transformation.

---

## Objective
The objective of this project is to:

- Transform NO₂ observations using a roll-number-based nonlinear transformation.
- Estimate the parameters **(λ, μ, c)** of the probability density function.

The transformed probability density function is defined as:

<img width="1202" height="239" alt="Screenshot 2026-02-18 004809.png" src="https://github.com/user-attachments/assets/60408621-2c7d-4370-8154-3e5e64536d22" />

Where:
- **λ (lambda)** represents the spread or precision parameter of the distribution.
- **μ (mu)** represents the mean of the transformed observations.
- **c** is the normalization constant ensuring the function behaves as a valid probability density function.

This model helps in understanding the statistical distribution of transformed NO₂ concentration values and demonstrates parameter estimation using real-world environmental data.

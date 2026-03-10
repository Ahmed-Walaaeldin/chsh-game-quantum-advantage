# CHSH Game: Quantum Advantage and Noise Analysis

A computational study of the **CHSH nonlocal game**, one of the most important protocols in quantum information theory.  
This project compares classical and quantum strategies, reproduces the Bell-inequality violation numerically, and studies how noise reduces the quantum advantage.

## Overview

The CHSH game is a two-player cooperative game that highlights the difference between **classical correlations** and **quantum entanglement**.

Classically, the maximum winning probability is **0.75**.

Quantum mechanically, with an optimal entangled strategy, the maximum winning probability is **cos²(π/8) ≈ 0.8536**.

This notebook verifies both results computationally and explores how the advantage changes under realistic noise.

## What this project does

- Explains the CHSH game and its significance
- Enumerates all deterministic classical strategies
- Verifies the classical maximum win rate of **75%**
- Implements the optimal **quantum CHSH strategy** with entangled qubits
- Computes:
  - empirical winning probability
  - CHSH correlators
  - the **S parameter**
- Compares results against:
  - Classical bound: **|S| ≤ 2**
  - Tsirelson bound: **|S| ≤ 2√2**
- Studies robustness under noise, including:
  - **Depolarizing noise**
  - **Readout noise**
- Uses repeated runs and statistical analysis for stability

## Key outcomes

- Confirms the classical CHSH limit of **0.75**
- Reproduces the optimal quantum advantage of about **0.8536**
- Demonstrates Bell inequality violation through simulation
- Shows how noise progressively reduces the winning probability and the CHSH violation

## Tools and libraries

- Python
- Qiskit
- Qiskit Aer
- NumPy
- Pandas
- Matplotlib

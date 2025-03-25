# Persistence Length of Conjugated Polymers using the Hindered Rotation Model

## Introduction

The reference paper [Predicting Chain Dimensions of Semiflexible Polymers from Dihedral Potentials](https://doi.org/10.1021/ma500923r) provides a detailed explanation of the method. The orginal codes were written in Mathematica. This repository aims to replicate the results using Python with code optimization.

* Code Optimization

  - Load external dihedral potential files.
  - Replace cos polyfit with cubic spline.
  - Replace recursion with cumsum.
  - Replace for loop with vectorization.
  - Calculation with 20 repeat units and 50000 samples can be done within 30 seconds.

## Requirements

- NumPy
- SciPy
- Matplotlib

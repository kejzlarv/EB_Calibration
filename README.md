# Supplementary code to "A Fast and Calibrated Computer Model Emulator: An Empirical Bayes Approach" by Kejzlar, Son, Bhattacharya, and Maiti (2020)

This repository contains complete Python code to reproduce the simulation and calibration of the Liquid drop model (LDM) in "A Fast and Calibrated Computer Model Emulator: An Empirical Bayes Approach."

The supplementary results for the sensitivity study are available upon request at vkejzlar@skidmore.edu.

## Content of jupyter notebooks with source code:
1. [Simulation](Simulation.ipynb) - Notebook with the complete implementation of EB approach for computer model enabled predictions of physical quantities. It contains source code to reproduce the simulation results under both MCMC and EB approaches.
2. [LDM](LDM.ipynb) - Self-sufficient notebok with implementation of both EB and MCMC based calibration of the Liquid Drop Model of nuclear binding energies.

## Content of supplementary files:
1. [AME2003 dataset](mass.mass03) - Raw dataset of experimental binding energies
2. [Even-Even nuclei from AME2003 dataset](BE_even_Z_even_N.csv) - Subset of AME2003 dataset used for the calibration of LDM
3. [AME2003 testing data](AME2003_test.pkl) - Testing dataset of Even-Even nuclei
4. [AME2003 training data](AME2003_train.pkl) - Training dataset of Even-Even nuclei
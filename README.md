This repository provides parameter points and analysis scripts accompanying our study on the two-Higgs-Doublet Model (2HDM).

## Overview
Our work focuses on the two-Higgs-doublet model with a softly broken $Z_2$ symmetry in the **Normal Scenario**,
where the observed 125 GeV Higgs boson is identified as the lighter CP-even neutral state ($h$).
We perform a comprehensive analysis across all four Yukawa types: **Type-I**, **Type-II**, **Type-X (Lepton-specific)**, and **Type-Y (Flipped)**.

- [arXiv:2607.09864 [hep-ph]](https://arxiv.org/abs/2607.09864) **Strong First-Order Electroweak Phase Transitions and Gravitational Waves in the Normal Two-Higgs-Doublet Model: A Comparative Study of the Four Yukawa Types and Thermal Resummation Schemes** by Jin-Hwan Cho, Dongjoo Kim, Jinheung Kim, Soojin Lee, and Jeonghyeon Song

## Gravitational Wave (GW) Parameter Points
We highlight parameter points that yield a potentially observable stochastic gravitational wave background (SGWB).
These points satisfy the detection threshold defined by a 4-year LISA signal-to-noise ratio: SNR > 10.

## Available Files
- [`GW_parameters.parquet`](GW_parameters.parquet): Contains the full dataset of parameter points satisfying the LISA SNR > 10 threshold.
- [`GW_parameters.ipynb`](GW_parameters.ipynb): A Jupyter notebook demonstrating how to load and filter the parameter points from the `.parquet` file.

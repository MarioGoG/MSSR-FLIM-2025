# MSSR-FLIM-2025

This repository contains Jupyter Notebooks for simulating, analyzing, and enhancing FLIM (Fluorescence Lifetime Imaging Microscopy) data. The methods include both Time-Domain (TD-FLIM) and Frequency-Domain (FD-FLIM) techniques, along with advanced resolution-enhancement algorithms such as Mean Shift Super Resolution (MSSR) applied to FLIM datasets.

## Notebooks Overview

| **Notebook Name**                                       | **Description**                                                                                                                                                                                                                       |
|---------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **01_FD-FLIM_simulator.ipynb**                          | **Frequency-Domain FLIM Simulation**: Simulates synthetic FLIM data using phase and modulation (FD) methods. Unlike conventional photon histogram-based techniques, this method simulates using phase and modulation data.                  |
| **02_TD-FLIM_simulator.ipynb**                          | **Time-Domain FLIM Simulation**: Simulates TCSPC (Time-Correlated Single Photon Counting) data with customizable lifetime parameters. It generates photon arrival histograms for time-domain FLIM analysis.                               |
| **05_TD-FLIM_MSSR.ipynb**                               | **MSSR on Beads**: Applies Mean Shift Super Resolution (MSSR) to simple TD-FLIM data, typically using bead samples, to demonstrate the resolution enhancement capabilities of the algorithm.                                           |
| **06_TD-FLIM_gatta-quant.ipynb**                         | **GATTA-Cells Analysis**: Performs standard lifetime imaging of 3-color GATTA-Cells samples using TD-FLIM methods. This notebook contains the basic workflow for analysis without the advanced MSSR quantitative metrics in later versions. |
| **09_Spatial diffraction-induced phasor.ipynb**          | **Diffraction Effects**: Theoretical analysis and simulation of how the Point Spread Function (PSF) leads to spatial averaging and phasor shifts at boundaries. This helps in understanding diffraction-induced distortions in FLIM data. |
| **v_08_TD_FLIM_3CGQ_2025_10_17_PhasorPy07.ipynb**       | **Advanced Experimental Analysis**: An advanced pipeline for analyzing 3-color GATTA-Cells with TD-FLIM. Includes MSSR-enhanced phasor segmentation, ROI-specific component analysis, quantitative cluster metrics, and PhasorPy 0.7 compatibility. |

## Requirements

To run the notebooks in this repository, ensure you have the following Python packages installed:

- `numpy`
- `scipy`
- `matplotlib`
- `pandas`
- `seaborn`
- `scikit-image`
- `PhasorPy` (specifically version 0.7 for `v_08_TD_FLIM_3CGQ_2025_10_17_PhasorPy07.ipynb`)
- `OpenCV` (for advanced image processing)

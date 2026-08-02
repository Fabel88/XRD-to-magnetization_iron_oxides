# Predicting Magnetization from X-ray Diffraction

This repository contains simulated datasets, trained machine-learning models, experimental datasets, crystallographic information files, and Jupyter notebooks used to predict the magnetization of iron oxide nanoparticles from X-ray diffraction (XRD).

The workflow uses simple physics-based models to generate paired XRD and magnetization data for training Random Forest and Gradient Boosting regression models. The trained models are then applied to experimental XRD measurements to predict maximum magnetization and full magnetization–field (M–B) curves, with comparison to corresponding magnetic measurement data for a given sample.

## Associated paper

**Machine Learning for Predicting Magnetization from X-ray Diffraction of Iron Oxide Nanoparticles Using Simple Physics-Based Data Generation**

Frank M. Abel, Paige Burke, Daniel Wines, Brian Donovan, Michelle E. Jamer, and Kamal Choudhary.

[arXiv:2512.13909](https://arxiv.org/abs/2512.13909)

## Repository structure

- `CIF/` — Crystallographic information files used to simulate XRD patterns.
- `Experimental_datasets/` — Experimental XRD and room-temperature M–B measurements.
- `Simulated_datasets/` — Physics-based simulated XRD and magnetization datasets stored as NumPy NPZ files.
- `Trained_models/` — Trained Random Forest and Gradient Boosting models, model metadata, and feature-importance results.
- `Notebooks/` — Jupyter notebooks for data generation, model training, analysis, plotting, and experimental inference.
- `Old_versions/` — Legacy files from the earlier repository structure.

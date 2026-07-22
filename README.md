# HD-MEA Longitudinal Neuron Tracking

## Overview

This repository provides an end-to-end Python pipeline for longitudinal analysis of neuronal activity recorded using High-Density Microelectrode Arrays (HD-MEA).

The pipeline integrates Kilosort4 spike sorting, waveform and template similarity, spatial validation, quality control, statistical analysis, and visualization to identify stable neuronal populations across multiple recording sessions.

The framework was developed during my M.Sc. thesis at the University of Naples Federico II for the analysis of capsaicin-induced neuronal activity recorded from innervated human skin equivalent (IHSE) models using the Maxwell Biosystems MaxOne HD-MEA platform.
## Workflow

```text
Raw HD-MEA Recordings
        │
        ▼
HDF5 Preprocessing
        │
        ▼
Kilosort4 Spike Sorting
        │
        ▼
Quality Control
        │
        ▼
Waveform & Template Matching
        │
        ▼
Spatial Validation
        │
        ▼
Longitudinal Neuron Tracking
        │
        ▼
Statistical Analysis
        │
        ▼
Publication-ready Figures
```

---

## Main Features

- HD-MEA data preprocessing
- Kilosort4 integration
- Quality-control pipeline
- Waveform extraction
- Longitudinal neuron matching
- Template similarity analysis
- Spatial validation
- Statistical analysis
- Publication-quality visualizations

---

## Technologies

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- H5py
- OpenPyXL

---

## Current Status

This repository is currently being organized for public release.

Code documentation and examples will be added progressively.
## Repository Structure

```
src/            Source code
notebooks/      Jupyter notebooks
figures/        Figures and visualizations
docs/           Documentation
data/example/   Example files
```

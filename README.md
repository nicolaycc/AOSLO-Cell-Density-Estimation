# AOSLO-Cell-Density-Estimation
This repository accompanies the thesis “Cell Density Estimation in AOSLO Images Using Image Processing and Deep Learning.” It contains all code, auxiliary data, and documentation required to reproduce the experiments, train the four proposed models, and generate every table and figure included in the paper.

[![License](https://img.shields.io/badge/Code-Apache--2.0-blue.svg)](LICENSE)
[![Data License](https://img.shields.io/badge/Data-CC%20BY--NC%204.0-lightgrey.svg)](data/README_DATA.md)
![Python 3.10+](https://img.shields.io/badge/python-3.10+-yellow.svg)

---

## Table of Contents
1. [Overview](#overview)  
2. [Key Features](#key-features)  
3. [Project Structure](#project-structure)  
4. [License](#license)  
5. [Authors & Contact](#authors--contact) 
6. [Disclaimer](#disclaimer)

---

## Overview
This repository accompanies the thesis **“Cell Density Estimation in AOSLO Images Using Image Processing and Deep Learning.”**  
It provides an end-to-end, reproducible pipeline for:

* Pre-processing Adaptive Optics Scanning Laser Ophthalmoscopy (AOSLO) images.  
* Training **four lightweight deep-learning models** for cone-density estimation.  
* Evaluating, visualising, and exporting results for publication‐ready figures.  
---

## Key Features
* **Four model variants**  
  *Model A – Lightweight U-Net*  
  *Model B – Lightweight U-Net + Linear Correction*  
  *Model C – U-Net + Global-Sum Regression*  
  *Model D – Encoder + Global Average Pooling (direct regression)*  
* **Reproducible training** with fixed seeds, `EarlyStopping`, and `ReduceLROnPlateau`.  
* **Notebook gallery** recreating every figure and table in the thesis.  
* **Clear licensing split**: code (Apache-2.0) vs. data (CC BY-NC 4.0).  

---

## Project structure
aoslo-cell-density-estimation/  
│  
├─ data/  
│  
├─ models/                
│  
├─ notebooks/             
├─ LICENSE                
└─ README.md              

---

## License
- Code: Apache License 2.0
- Data & pre-processed labels: CC BY-NC 4.0

NOTE: This repository contains research code not intended for diagnostic use in clinical practice. No warranty is provided.

---

## Authors & Contact
Nicolay Cortez  
Santiago Toledo

---
## Disclaimer

This software is provided “as is” for research purposes only.
It has not been approved for clinical diagnostics and must not be used to guide patient care without appropriate validation and regulatory clearance.
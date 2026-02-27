# Example Repository for Cooling Population Analysis

This repository provides example scripts and processed data.

It is intended as a lightweight demonstration repository.

---

## Repository Structure

This repository contains two main folders:

### 1. Code

The `Code` folder contains example scripts and notebooks.  
Each script includes detailed descriptions of the data used and the processing steps.

### 2. Data

The `Data` folder provides post-processed results only.

Raw CESM outputs are not included because CESM simulations generate large and complex datasets.  
Providing processed results improves efficiency and usability.

---

## CESM2 Requirements

CESM simulations must be run on high-performance computing (HPC) systems.

Model runtime depends on computational resource configuration and system settings.

For detailed information, please refer to the official CESM2 documentation:

https://www.cesm.ucar.edu/models/cesm2

---

## OSCAR Requirements

OSCAR can be run on a personal computer and does not require HPC resources.

Before running OSCAR, Python must be installed.

Required Python packages include:

- xarray (v0.20.1)
- netCDF4 (v1.5.7)
- numpy (v1.23.3)
- scipy (v1.9.3)

OSCAR has significantly lower computational demands compared to CESM.

For detailed information, please refer to the OSCAR documentation:

https://github.com/tgasser/OSCAR


---

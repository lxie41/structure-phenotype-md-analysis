# MDPPM Structure–Phenotype Analysis

This repository contains the Jupyter notebook used for the analysis of mutation-dependent conformational dynamics in PTEN, KRAS, and MEK1.

## Data Availability

Processed datasets are available via Zenodo:

**DOI:** https://doi.org/10.5281/zenodo.19268556

Download the datasets and place them in a local `data/` directory:
data/
├── PTEN.csv
├── KRAS.csv
├── MEK1.csv


## How to Run

1. Open the notebook:
pten_ml_dt_circular.ipynb


2. By default, the notebook is configured for the **PTEN** dataset.

3. To run the analysis for **KRAS** or **MEK1**, update:
   - the input data file path  
   - and any dataset-specific parameters that are currently hard-coded  

4. Run all cells to reproduce the analysis.

## Requirements

- Python 3  
- NumPy  
- Pandas  
- scikit-learn  
- Matplotlib  

## Notes

- The notebook was primarily developed using the **PTEN** dataset.  
- Running the analysis on **KRAS** and **MEK1** may require minor adjustments to data paths and certain hard-coded parameters.  
- The provided datasets correspond to processed feature matrices used in the study.  
- Full MD trajectories are not included due to file size limitations.  

## Arthor
Longsheng Xie lxie2@gmu.edu


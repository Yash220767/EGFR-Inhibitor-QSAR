# EGFR-Inhibitor-QSAR
This repository contains the computational workflow for developing a Quantitative Structure-Activity Relationship (QSAR) model to predict the inhibitory potency of molecules against the Epidermal Growth Factor Receptor (EGFR).

Project Overview:
The goal of this research is to identify key molecular descriptors that drive EGFR inhibition and build a predictive machine learning pipeline. This work is part of my dissertation research conducted during my internship at AiSense LLP.
## Dataset
- Source: ChEMBL database
- Target: EGFR (Epidermal Growth Factor Receptor)
- Bioactivity metric: IC50 values
- Application: Non-small cell lung carcinoma (NSCLC)

## Workflow
1. Data curation and preprocessing from ChEMBL
2. Molecular descriptor and Morgan fingerprint calculation using RDKit
3. Feature selection and scaffold split
4. Model building — Random Forest and SVM classifiers
5. Model validation and performance evaluation

## Tools & Libraries
- Python 
- RDKit
- Pandas, Matplotlib

## Status
Work in progress — updated regularly 

## Note
Raw dataset not included in this repository. Source data available via the [ChEMBL database](https://www.ebi.ac.uk/chembl/).

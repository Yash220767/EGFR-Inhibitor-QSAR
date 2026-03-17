# EGFR-Inhibitor-QSAR
This repository contains the computational workflow for developing a Quantitative Structure-Activity Relationship (QSAR) model to predict the inhibitory potency of molecules against the Epidermal Growth Factor Receptor (EGFR).

Project Overview
The goal of this research is to identify key molecular descriptors that drive EGFR inhibition and build a predictive machine learning pipeline. This work is part of my dissertation research conducted during my internship at AiSense LLP.

Current Progress
Data Acquisition: Retrieved raw EGFR inhibitor data from public repositories (ChEMBL).

Data Cleaning: 
Removed incomplete entries and standardized chemical structures.Feature Engineering: - Generated 217 molecular descriptors using RDKit.
Filtered features via Variance Thresholding.
Removed highly redundant descriptors ($|r| > 0.90$), streamlining the matrix to 130 high-quality features.

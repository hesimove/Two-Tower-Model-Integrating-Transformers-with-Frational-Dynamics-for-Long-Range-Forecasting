# Two-Tower Model Integrating Transformers with Fractional Dynamics for Long-Range Forecasting

This repository contains the code and experiments for our paper:
**"Two-Tower Model: Integrating Transformers with Fractional Dynamics for Long-Range Forecasting"**.

## Overview
We propose a hybrid two-tower architecture:
- **Transformer tower:** Captures raw temporal dependencies.
- **Fractional Dynamics tower:** Encodes long-memory and structural inductive bias.
- **Fusion module:** Combines both representations for robust time-series classification and forecasting.

## Repository Structure
- `notebooks/` – Jupyter Notebooks for model training and evaluation  
- `results/` – Experimental results and visualizations  
- `save_loss/` – Notebooks/scripts for saving loss  

## References
- **Dataset:** UCR Time Series Archive (2018) — https://www.cs.ucr.edu/~eamonn/time_series_data_2018/  
- **Data Processing Code:** Adapted from  
  Fractional-dynamics-foster-deep-learning-of-COPDstage-prediction — https://github.com/chenzhoy/Fractional-dynamics-foster-deep-learning-of-COPDstage-prediction

## Results
Our model outperforms strong baselines (Informer, FEDformer, TS2Vec) on multiple UCR datasets, with gains up to **+17% AUC** and **+30% Accuracy**.

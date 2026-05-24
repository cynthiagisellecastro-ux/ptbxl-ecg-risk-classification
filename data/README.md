# Data Usage Guide

The full PTB-XL Electrocardiography Database is not stored in this GitHub repository because the raw ECG waveform files are large.

This repository includes the project code, notebook, documentation, and instructions needed to reproduce the data setup. The dataset should be downloaded directly from Kaggle or PhysioNet.

## Dataset

**Dataset name:** PTB-XL Electrocardiography Database  
**Source:** PhysioNet / Kaggle  
**Kaggle dataset:** `physionet/ptbxl-electrocardiography-database`  
**PhysioNet dataset:** PTB-XL Electrocardiography Database  

## Required Files

The notebook uses the following metadata files:

- `ptbxl_database.csv`
- `scp_statements.csv`

These files are used to create the modeling target and map ECG diagnostic codes to broader diagnostic classes.

## How to Download the Data

You can download the dataset from Kaggle using the Kaggle API:

```bash
kaggle datasets download -d physionet/ptbxl-electrocardiography-database -p data --unzip

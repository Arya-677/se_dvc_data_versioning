# se_dvc_data_versioning
# DVC Data Versioning

A simple demonstration of using **Git and DVC (Data Version Control)** to manage and version datasets.

## Project Overview

This project demonstrates how Git can be used for code versioning while DVC can be used to track and manage changes to data files.

The project contains a small sample dataset and a Python script that demonstrates switching between different versions of the dataset.

## Files

- `data.csv` – Sample dataset containing features and labels.
- `demo_checkout.py` – Python script demonstrating how to switch between dataset versions.
- `README.md` – Project documentation.

## Dataset

The dataset contains three columns:

| Column | Description |
|--------|-------------|
| `id` | Unique identifier for each data record |
| `feature` | Numerical feature value |
| `label` | Target/class label |

Example:

```csv
id,feature,label
1,0.5,1
2,1.2,0
3,2.1,1
4,1.8,0

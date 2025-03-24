# SustainBench Crop Yield Replication
This repository contains code and data for replicating the U.S. soybean yield prediction task from [SustainBench](https://github.com/sustainlab-group/sustainbench).

## Requirements
- Python 3.8+
- Jupyter Notebook
- scikit-learn, numpy, etc.

## Setup
1. Clone this repository
2. Install dependencies via `pip install -r requirements.txt`
3. Launch Jupyter Notebook and open `notebook/soybean_yield.ipynb`
4. Run all cells to reproduce the results
/
Please note: Model training may take a while, so please be patient while the computations complete...


## Data
The `data/` folder contains pre-split NPZ files (`train_hists.npz`, `train_yields.npz`, etc.) from SustainBench.

## Results
Validation RMSE ~0.356 t/ha, R² ~0.732  
Test RMSE ~0.344 t/ha, R² ~0.746


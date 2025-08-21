# Time Series Forecasting of Taco Sales
This repository contains my individual contribution from a larger group project, focusing exclusively on **time series analysis and forecasting** of taco sales data. It explores data preprocessing, visualization, and modeling sales trends using statistical and neural network approaches.

It includes the following files:
- `Taco_TimeSeries.ipynb` — Jupyter Notebook with full analysis, visualizations, and forecasting results.  
- `Taco_TimeSeries.py` — Script version of the notebook for a cleaner, software-style implementation.  
- `README.md` — Project description, setup instructions, and documentation. 

## Dataset
- Source: [Kaggle Taco Sales Dataset (2024–2025)](https://www.kaggle.com/datasets/atharvasoundankar/taco-sales-dataset-20242025/data)  
- License: MIT (see dataset page for details).  

## Methods
The notebook demonstrates:
- Data exploration and preprocessing
- Time series visualization
- Forecasting with Recurrent Neural Networks (RNNs)

## Quickstart
```bash
# 1) Clone
git clone <your-repo-url>.git
cd taco-time-series

# 2) Create environment (pip)
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# 3) Launch
jupyter lab   # or jupyter notebook

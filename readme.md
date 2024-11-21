# Welding Parameter Prediction Model

## Overview
Machine learning model for predicting welding quality parameters (Quality Width and Depth Penetration) based on process parameters. The model uses XGBoost to achieve R² scores > 0.92 for both target variables.

## Requirements
- Python 3.8+
- Required packages listed in `requirements.txt`

## Installation

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment

Windows:
```bash
venv\Scripts\activate
```

Unix/MacOS:
```bash
source venv/bin/activate
```

Install dependencies
```bash 
pip install -r requirements.txt
```

## Project Structure
- `ml_analysis.ipynb`: Main analysis notebook
- `requirements.txt`: Project dependencies
- `data/`: Input datasets (not tracked in git)
- `models/`: Saved model files (not tracked in git)

## Model Performance
- Quality Width (QW): R² = 0.9237, SMAPE = 2.27%
- Depth Penetration (DP): R² = 0.9732, SMAPE = 4.87%

## Usage
Open and run `ml_analysis.ipynb` in Jupyter Notebook:

```bash
jupyter notebook ml_analysis.ipynb
```
# A Journey Toward a Suitable Predictive Model

This repository contains the code used to reproduce all results, figures, and experiments from the article **"A Journey Toward a Suitable Predictive Model."** for the Henkel Data & Analytics Blog. The article explores how different models behave when predicting product sales and shows why the most useful model is the one that fits the structure of the problem, not necessarily the most accurate one.

## Contents

- `notebooks/`   
  - `synthesize_dataset.ipynb` - creates a synthetic dataset for experimentation
  - `modeling_journey_on_synthetic_data.ipynb` - reproduces the modeling journey from the article
- `requirements.txt` - python dependencies for running everything locally


## How to Reproduce the Results

1. Create the environment using `requirements.txt`. Example for Windows (powershell):

```powershell
python -m venv .venv 
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

2. Regenerate the synthetic dataset by running the notebook `synthesize_dataset.ipynb`

3. Run notebook `modeling_journey_on_synthetic_data.ipynb`

# Machine_Learning_Classification

This repository contains Jupyter notebooks and data for an employee-related machine learning classification/regression project originally from HackerEarth.

## What is in this repo

- Notebooks:
	- `Employee_main.ipynb` — main notebook (data prep, modeling, includes TensorFlow example)
	- `Emp_Random_forest_1.ipynb` — Random Forest classifier analysis
	- `Emp_Random_forset_2.ipynb` — Random Forest / XGBoost experiments (typo in filename preserved)
	- `Employee-old.ipynb` — older iteration
- Data:
	- `Train.csv` — training dataset
	- `Test.csv` — test dataset

## Dependencies

Install the Python dependencies listed in `requirements.txt`. These were inferred from the notebooks (pandas, numpy, scikit-learn, tensorflow, seaborn, matplotlib, scipy, xgboost, openpyxl, jupyter). Adjust versions if you encounter compatibility issues.

To install:

```bash
pip install -r requirements.txt
```

Recommended Python version: 3.8 or newer.

## How to run

1. Create a virtual environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2. Start Jupyter Lab / Notebook and open the notebook you want to run:

```bash
jupyter notebook
# or
jupyter lab
```

3. Open e.g. `Emp_Random_forest_1.ipynb` and run the cells. The notebooks read `Train.csv` / `Test.csv` from the repository root, so ensure those files are present.


## License

This repository appears to be a personal project or a HackerEarth challenge solution.
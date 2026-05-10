# FamilyEDA

Exploratory data analysis (EDA) of the `ds.csv` dataset, focusing on family history, eating habits, physical activity, and transportation choices in relation to obesity classification.

## Repository contents

- `Solution.ipynb` — Jupyter notebook with EDA plots and summaries.
- `ds.csv` — Source dataset (2,111 rows, 19 columns).

## Dataset

Columns:

- Gender
- Age
- family_history_with_overweight
- FAVC
- FCVC
- NCP
- CAEC
- SMOKE
- CH2O
- SCC
- FAF
- TUE
- CALC
- Automobile
- Bike
- Motorbike
- Public_Transportation
- Walking
- NObeyesdad (target)

## Setup

Use Python 3 and install the notebook dependencies:

```bash
pip install numpy pandas seaborn matplotlib jupyter
```

## Usage

Run the notebook from the repository root:

```bash
jupyter notebook Solution.ipynb
```

The notebook expects `ds.csv` to be in the same directory.

# Sonar Rock vs Mine Prediction

A machine learning project that predicts whether an object is a **Rock (R)** or **Mine (M)** using sonar signal data and Logistic Regression.

## Files

- `sonar Rock vs mine prediction.ipynb` - main notebook
- `requirements.txt` - Python dependencies

## Dataset

This notebook now loads the dataset directly from a public URL:

- https://archive.ics.uci.edu/ml/machine-learning-databases/undocumented/connectionist-bench/sonar/sonar.all-data

The dataset has 60 numeric features and 1 label column (`R` or `M`).

## Setup

1. Create and activate a virtual environment (recommended).
2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Run

1. Open the notebook:

```bash
jupyter notebook
```

2. Run all cells in `sonar Rock vs mine prediction.ipynb`.

## Notes

- The notebook uses a direct dataset URL, so no local `sonar.csv` file is required.
- If you want offline usage later, you can download the dataset and read it locally.

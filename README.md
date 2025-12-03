# IDS2025 – Melting Point Prediction (Group G1)

This repository contains all code, notebooks and submission files for the IDS2025 project.
It is structured so that another student or instructor can fully reproduce the analysis and rerun all experiments.

## Kaggle Competition Link

This project is based on the Kaggle challenge:

### https://www.kaggle.com/competitions/melting-point/overview

---

## Repository Structure

ids2025_group7_project_g1/
│
├── Data/
│ ├── train.csv # Kaggle training data
│ ├── test.csv # Kaggle test data
│ └── helper/ # Additional data used by the Optuna notebook
│
├── Graphics/ # for Poster
│
├── Jupyter Notebooks/
│ ├── DataExploration.ipynb
│ ├── DataExploration_PCA_Clustering.ipynb
│ ├── RandomForest_SVR.ipynb
│ ├── RandomForest_SVR_with_FeatureEngineering.ipynb
│ ├── Regression.ipynb
│ ├── neural_networks.ipynb
│ ├── Ensemble.ipynb
│ ├── **melting-point-optuna-optimized.ipynb** # requires Data/helper
│ ├── G1_report.ipynb
│ └── Plotting.ipynb
│
├── Submissions/ # all submission-csv´s
│
└── G1_report.pdf # report
└── qrcode_www.kaggle.com.png # for poster
└── README.md

## How to Run the Code

You need:

- Python 3.9+
- Jupyter Notebook / JupyterLab
- Standard scientific libraries (`numpy`, `pandas`, `matplotlib`, `scikit-learn`)
- ML libraries:
  - `xgboost`
  - `lightgbm`
  - `catboost`
  - `optuna`
  - `rdkit` (for feature engineering)

## Notebook Overview & Execution Instructions

All notebooks can be opened and executed in any Jupyter environment.
Below is what each notebook does and in which order they may be used.

You can also run all notebooks directly on Kaggle by uploading the repository.
This usually results in better performance

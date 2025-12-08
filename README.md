# IDS2025 – Melting Point Prediction (Group G1)

This repository contains all code, notebooks and submission files for the IDS2025 project.
It is structured so that another student or instructor can fully reproduce the analysis and rerun all experiments.

## Kaggle Competition Link

This project is based on the Kaggle challenge:

https://www.kaggle.com/competitions/melting-point/overview

---

## Repository Structure

```text
ids2025_group7_project_g1/
│
├── Data/
│   ├── train.csv                  # Kaggle training data
│   ├── test.csv                   # Kaggle test data
│   └── helper/                    # Additional data used by the Optuna notebook
│
├── Graphics/                      # Figures and graphics for the poster
│
├── Jupyter Notebooks/
│   ├── DataExploration.ipynb                           # basic dataset overview
│   ├── DataExploration_PCA_Clustering.ipynb            # structural patterns & clustering
│   ├── RandomForest_SVR.ipynb                          # baseline rf/svr models
│   ├── RandomForest_SVR_with_FeatureEngineering.ipynb  # rf/svr with rdkit features
│   ├── Regression.ipynb                                # linear regression models
│   ├── neural_networks.ipynb                           # deep learning baseline
│   ├── Ensemble.ipynb                                  # combined model predictions
│   ├── melting-point-optuna-optimized.ipynb            # final optimized model
│   ├── G1_report.ipynb                                 # report generation notebook
│   └── Plotting_KNN.ipynb                              # figures for report and KNN model
│
├── Submissions/                   # all Kaggle submission CSVs
│
├── G1_report.pdf                  # project report HW10
├── qrcode_www.kaggle.com.png      # QR code for the poster
└── README.md

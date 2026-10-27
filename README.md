# Predicting Credit Card Default

CT4101 Machine Learning portfolio project. Diarmuid O'Shea, 23465914.

## Question

Can a credit card client's default on next month's payment be predicted from their credit limit, demographics and six months of billing and payment history? Binary classification.

## Dataset

Default of Credit Card Clients, UCI Machine Learning Repository (dataset 350). 30,000 clients of a Taiwanese bank, April to September 2005. Licence: CC BY 4.0.

Yeh, I. (2009). Default of Credit Card Clients [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C55S3H

The CSV used is the Kaggle copy: https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset
Save it as data/UCI_Credit_Card.csv.

## Folders

- data/ : the dataset
- notebooks/01_data_audit_and_baseline.ipynb : Milestone 2 work (audit, cleaning, split, preprocessing, baselines)
- requirements.txt : packages and versions
- ASSISTANCE.md : assistance declaration

## Setup (Windows PowerShell, Python 3.14)

python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt

## Run

jupyter lab

Open notebooks/01_data_audit_and_baseline.ipynb and use Run > Restart Kernel and Run All Cells.
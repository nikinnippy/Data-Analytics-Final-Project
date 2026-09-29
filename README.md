# Data Analytics Final Project – Loan Approval Prediction

## Student
**Nikin Babu**

## Domain
**Finance and Banking**

## Project Objective
The objective of this project is to analyse loan application data and identify patterns associated with loan approval and rejection using Python-based data analytics.

## Dataset
**Loan Approval Prediction Dataset**

- Source: Kaggle
- Records: 4,269
- Original variables: 13
- Target variable: `loan_status`
- Outcomes: Approved / Rejected

## Project Workflow
1. Problem Definition & Dataset Selection
2. Data Loading and Initial Overview
3. Data Cleaning & Pre-processing
4. Exploratory Data Analysis (EDA)
5. Statistical Summary
6. Insight Generation and Report
7. Conclusion and Recommendations

## Data Pre-processing
The project includes checks for:
- Missing values
- Duplicate records
- Data types and formatting
- Invalid numerical values
- Derived features

Two derived features were created:
- `loan_to_income_ratio`
- `total_asset_value`

During validation, 28 invalid residential asset values of `-100000` were identified and converted to missing values (`NaN`) while retaining the corresponding loan records.

## Key Findings
- Approved applications represent approximately 62.22% of the dataset.
- Rejected applications represent approximately 37.78%.
- CIBIL score showed the strongest observed difference between approved and rejected applications.
- Mean CIBIL score was approximately 703 for approved applications versus 429 for rejected applications.
- Education and self-employment showed very similar approval rates.
- Annual income and loan amount showed relatively small differences between the two groups.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Repository Contents
- `Data_Analytics_Final_Project_GitHub.ipynb` – completed project notebook
- `loan_approval_dataset.csv` – original/raw dataset

## How to Run
1. Download or clone this repository.
2. Keep the notebook and `loan_approval_dataset.csv` in the same folder.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run the notebook from the beginning.

## Note
The notebook is designed to load the dataset using the relative file path `loan_approval_dataset.csv`, so it can be run from the repository without relying on the Google Colab `/content/` path.

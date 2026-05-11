# Visa Approval Prediction System

**Domain:** Applied ML / Decision Science  
**Part of:** UT Austin PG Program in AI & ML

## Objective

Predict U.S. visa certification outcomes and identify significant drivers influencing approval or denial decisions.

## Key Focus Areas

- Policy-oriented classification
- Feature impact analysis
- Decision-support insights
- Handling imbalanced classes (e.g. SMOTE, class weights)

## How to Run

1. Open `EasyVisa_Submission.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure `EasyVisa.csv` is in the same folder (included in repo).
3. Install dependencies if needed (e.g. `xgboost`, `scikit-learn`, `imbalanced-learn`). The notebook may include `pip install` cells.
4. Run all cells sequentially.

## Files in This Folder

| File | Description |
|------|-------------|
| `EasyVisa_Submission.ipynb` | Main notebook (EDA, preprocessing, classification, evaluation) |
| `EasyVisa_Submission.html` | Exported HTML report |
| `EasyVisa.csv` | Visa certification dataset |

## Key Libraries

- Python, Pandas, NumPy
- Scikit-learn (preprocessing, classification, metrics, model selection)
- XGBoost
- Imbalanced-learn (e.g. SMOTE)
- Matplotlib, Seaborn
- Jupyter Notebook

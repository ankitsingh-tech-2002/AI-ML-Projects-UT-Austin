# Wind Turbine Predictive Maintenance

**Domain:** Industrial ML / Cost-Sensitive Learning  
**Part of:** UT Austin PG Program in AI & ML

## Objective

Predict wind turbine generator failures using sensor data to optimize inspection, repair, and replacement costs.

## Key Focus Areas

- Cost-sensitive classification
- False positive vs false negative trade-offs
- Maintenance strategy optimization
- Feature engineering and model tuning

## How to Run

1. Open `ReneWind_Project.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure `Train.csv` and `Test.csv` are in the same folder (included in repo).
3. Install dependencies (e.g. `tensorflow` or `keras`, `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`). The notebook may include `pip install` cells.
4. Run all cells sequentially. Training may take a while depending on hardware.

## Files in This Folder

| File | Description |
|------|-------------|
| `ReneWind_Project.ipynb` | Main notebook (EDA, preprocessing, modeling, cost-sensitive evaluation) |
| `ReneWind.html` | Exported HTML report |
| `Train.csv` | Training sensor data |
| `Test.csv` | Test sensor data |

## Key Libraries

- Python, Pandas, NumPy
- Scikit-learn (preprocessing, metrics, model selection, permutation importance)
- TensorFlow / Keras (neural networks)
- Matplotlib, Seaborn
- Jupyter Notebook

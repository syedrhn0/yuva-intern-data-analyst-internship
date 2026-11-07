# YuvaIntern Data Science Internship Submission

Six task-wise submissions using the scikit-learn diabetes research dataset.

## Dataset
442 observations, ten numeric baseline features and a quantitative target measuring disease progression one year after baseline. The features are pre-scaled. Source: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

## Structure
- `data/raw/`: source dataset export
- `data/processed/`: cleaned dataset export
- `notebooks/`: six runnable task notebooks
- `reports/`: six Word reports and CSV analysis outputs
- `visuals/`: charts for EDA and model evaluation
- `submission_descriptions/`: six portal descriptions (each over 200 words)

## Run
```bash
pip install -r requirements.txt
jupyter notebook
```
Run notebooks from the repository root.

## Models
Linear Regression, Ridge Regression and Random Forest Regressor. Evaluation: MAE, RMSE, R-squared and five-fold cross-validation MAE. See `reports/model_comparison.csv`.

## Limitations
This small, preprocessed research dataset is not suitable for clinical decisions. Correlation does not prove causation and model results do not establish real-world clinical performance.

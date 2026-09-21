# Week 4 - Predictive Modeling for Agriculture Applications

## Crop Yield Prediction

This project develops a machine learning framework for predicting crop yield from agricultural and environmental data.

### Objectives
- Define an agricultural prediction problem.
- Prepare crop-yield data for machine learning.
- Compare regression algorithms.
- Evaluate models using MAE, RMSE, and R².
- Create a reusable prediction workflow.

### Models
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

### Feature Engineering
The workflow includes:
- Missing-value handling
- Duplicate removal
- Numerical and categorical feature separation
- One-hot encoding
- Identification of irrelevant identifier columns
- Preparation of agricultural and environmental variables

### Evaluation
The project uses:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Folder Structure

```text
Week-4-Crop-Yield-Prediction/
├── Week_4_Crop_Yield_Prediction.ipynb
├── data/
│   └── crop_yield_dataset.csv
├── README.md
└── requirements.txt
```

### How to Run

1. Install Python 3.
2. Install the required packages:
   `pip install -r requirements.txt`
3. Put the crop yield CSV inside the `data` folder.
4. Open the Jupyter Notebook.
5. If necessary, change the `DATA_PATH` and `TARGET` variables.
6. Run the notebook from top to bottom.

### Note
The numerical model results should be generated from the actual project dataset. This repository does not fabricate performance values.

# House Price Prediction

A machine learning project that predicts California housing prices using a Random Forest Regressor.

## What `main.py` Does

- Loads the California housing dataset from `housing.csv`
- Splits the data into training and test sets using stratified sampling based on income
- Builds a preprocessing pipeline that imputes missing values, scales numerical features, and one-hot encodes the `ocean_proximity` column
- Trains a **Random Forest Regressor** and saves the model (`model.pkl`) and pipeline (`pipeline.pkl`)
- On subsequent runs, loads the saved model and runs predictions on the test set, saving results to `output.csv`

## How to Use

1. **Install dependencies**
   ```
   pip install pandas numpy scikit-learn joblib
   ```

2. **Train the model** — run the script for the first time:
   ```
   python main.py
   ```
   This trains the model and saves `model.pkl` and `pipeline.pkl`.

3. **Run predictions** — run the script again:
   ```
   python main.py
   ```
   Predictions are saved to `output.csv`.

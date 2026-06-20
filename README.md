# House Price Prediction

A machine learning project that predicts California housing prices using a Random Forest Regressor.

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

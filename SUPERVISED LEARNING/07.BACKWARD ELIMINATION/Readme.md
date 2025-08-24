This project applies **Backward Feature Elimination** to select the most significant features for regression.

## 🔹 Key Concepts
- Start with all features.
- Iteratively remove the **least significant predictor** (highest p-value).
- Refit the model until only statistically significant variables remain.

## 📦 Libraries
- `statsmodels`
- `sklearn`

## 📊 Outputs
- Final regression equation with selected features.
- Adjusted R² values.

## 🚀 How to Run
```bash
python main.py

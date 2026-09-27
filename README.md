# Car Price Prediction

Predicts the selling price of a used car using regression models, based on features like manufacturing year, present (ex-showroom) price, fuel type, and kilometers driven.

## Dataset
`data/car data.csv` — contains used car listings with fields: Year, Present_Price, Kms_Driven, Fuel_Type, Seller_Type, Transmission, Owner, Selling_Price.

## Approach
1. Load and clean the data (drop duplicates, encode categorical fuel type)
2. Exploratory data analysis — correlation heatmap, price distribution, feature vs price scatter plots
3. Train-test split (80/20)
4. Train and compare two models:
   - Linear Regression
   - Random Forest Regressor
5. Evaluate using R² score and RMSE

## Results
*(Fill in your actual R² and RMSE numbers here after running the notebook)*

| Model | R² | RMSE |
|---|---|---|
| Linear Regression | — | — |
| Random Forest | — | — |

## How to Run
```bash
pip install pandas scikit-learn seaborn matplotlib
jupyter notebook car_price_prediction.ipynb
```

## Next Steps
- Add more features (Transmission, Seller_Type, Owner)
- Try Ridge / Lasso regression
- Hyperparameter tuning for Random Forest

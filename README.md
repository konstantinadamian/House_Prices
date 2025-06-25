# House Price Prediction with SQLite and Machine Learning

This project predicts house prices using data from a SQLite database and machine learning models.

## What It Includes

- Connection to a SQLite database and merging of 3 tables:
  - `houses`: house features
  - `cities`: crime rates by city
  - `energy_classes`: tax rate by energy class
- Dataset creation with:
  - Data cleaning and preprocessing
  - Visualizations (e.g., heatmap,scatter,boxplot)
- Training of 2 models:
  - Linear Regression ✅ (best performance)
  - Decision Tree Regression

##  Results

Using 10-Fold Cross Validation:
- **Linear Regression** had lower RMSE and better prediction accuracy.

## Tools Used

- Python, SQLite  
- Pandas, Scikit-learn  
- Seaborn, Matplotlib

## License

MIT License

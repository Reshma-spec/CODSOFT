# Sales Prediction using Python

Predict product sales based on advertising spend across TV, Radio, and Newspaper channels.  
This project uses **Linear Regression** and **Random Forest** to forecast sales, helping businesses optimise their marketing budgets.

## Features
- Data loading and exploratory data analysis (EDA)
- Visualisation of relationships (pairplots, correlation heatmaps)
- Train/test split and model training
- Performance evaluation (MAE, RMSE, R²)
- Prediction for new advertising budgets
- Comparison with Random Forest regressor

## Dataset
The classic **Advertising dataset** (200 observations) – spend in thousands of dollars, sales in thousands of units.

## Requirements
- Python 3.7+
- pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Run
1. Clone the repository  
   `git clone https://github.com/yourusername/sales-prediction.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Run the Jupyter notebook `sales_prediction.ipynb`

## Results
- Linear Regression R² ≈ **0.90**
- TV ad spend has the strongest impact on sales

## Example Prediction
Spending $150k on TV, $30k on Radio, $20k on Newspaper → predicted sales ≈ **$16,870**

## Author
Your Name – [GitHub Profile Link]

## License
MIT

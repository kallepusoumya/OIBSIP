# Retail Sales and Nutrition Data Analysis

This project performs exploratory data analysis (EDA) on two datasets: retail sales data and a nutrition menu dataset.

## Datasets

- **Retail Sales Dataset** (`retail_sales_dataset.csv`): Contains 1000 rows and 9 columns with numerical and categorical features related to retail sales, including transaction details, customer demographics, and product information.
- **Menu Dataset** (`menu.csv`): A nutrition dataset with information on food items, including calories, fat, sugar, protein, sodium, and carbohydrates.

## Analysis Overview

The analysis is conducted in the Jupyter notebook `retail_eda.ipynb` and covers:

### Retail Sales Data
- Data cleaning and preprocessing (handling missing values, duplicates, data types).
- Distribution of total sales amounts.
- Sales by product category.
- Gender-wise spending analysis.
- Age distribution and relationship with spending.
- Quantity and price per unit vs. total amount.
- Monthly sales trends.

### Nutrition Data
- Calories distribution.
- Average calories by food category.
- Relationships between nutrients (fat, sugar, protein, sodium, carbohydrates) and calories.

## Key Insights

- Retail transactions are mostly low-value purchases.
- Certain product categories drive higher sales.
- Spending patterns differ by gender and age.
- Higher quantities and unit prices correlate with higher total amounts.
- Sales show seasonal variations.
- Nutrition-wise, most items have moderate calories, with variations by category and nutrient content.

## Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn

Install via pip:
```
pip install pandas matplotlib seaborn
```

## Usage

1. Ensure the datasets (`retail_sales_dataset.csv` and `menu.csv`) are in the same directory as the notebook.
2. Open `retail_eda.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to reproduce the analysis.

## Files

- `retail_eda.ipynb`: Main analysis notebook.
- `retail_sales_dataset.csv`: Retail sales data.
- `menu.csv`: Nutrition menu data.

## Troubleshooting

- If plots do not display, ensure matplotlib and seaborn are installed and a display backend is available.
- For data loading errors, verify file paths and CSV formats.
# Customer Behavior & Sales Insights

## Objective
Analyze Olist Brazilian e-commerce data to understand product revenue, customer repeat purchasing, payment preferences, delivery performance, and review scores.

## Tools
- Python
- pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Dataset
Download the [Brazilian E-Commerce Public Dataset by Olist on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). Keep the required CSV files together in a folder and set `DATA_DIR` in the notebook. Dataset files are not included in this repository.

## Run
1. Install dependencies: `pip install -r requirements.txt`
2. Download and extract the dataset.
3. Set `DATA_DIR` to the extracted folder.
4. Open `customer-behavior-sales-insights.ipynb` and run all cells from top to bottom.

## Analysis
- Monthly product revenue and sales KPIs
- Revenue by product category
- One-time vs. repeat customer behavior
- High-spend customers
- Payment methods
- Delivery-time and late-delivery analysis
- Review scores and delivery/review association

## Notes
Revenue uses item price and excludes freight. Delivery/review comparisons show association, not causation. Add numerical findings after running the notebook locally.

# Supply Chain Demand Forecasting & Inventory Optimization

## Project Overview
This project leverages Machine Learning to enhance supply chain efficiency using the **DataCo Smart Supply Chain Dataset**. The goal is to predict future product demand and determine optimal inventory levels (Safety Stock and Reorder Points) to prevent stockouts while minimizing overstock.

## Key Features
- **Data Cleaning**: Standardized column names, handled missing values, and converted order/shipping dates into time-series formats.
- **Demand Forecasting**: Utilized the **Prophet** library for time-series forecasting to predict weekly order quantities.
- **Inventory Metrics**: Calculated critical supply chain KPIs:
  - **Safety Stock**: Extra inventory held to mitigate risk of stockouts.
  - **Reorder Point (ROP)**: The specific level at which new stock must be ordered.
- **Visualizations**: Generated comparison plots between actual and forecasted demand, safety stock levels, and reorder points.

## Tools & Technologies
- **Python**: Core programming language.
- **Pandas/NumPy**: Data manipulation and numerical analysis.
- **Prophet**: Time-series forecasting.
- **Matplotlib/Seaborn**: Data visualization.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Open `supply-chain-ml.ipynb` in Jupyter or Kaggle.
4. Ensure the dataset path matches your local directory.

## Results
The model successfully identifies patterns in weekly demand, allowing for a forecasted safety stock that adapts to market trends, significantly improving replenishment strategy accuracy.

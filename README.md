**Sales Forecasting**

This repository contains a Jupyter Notebook (Sales_Forecasting.ipynb) that demonstrates the process of sales forecasting for a retail store. The goal of this project is to predict future sales for different categories of products, including furniture, office supplies, and technology, using time series forecasting techniques.

**Data**

The dataset used for this project includes historical sales data for the retail store, including the date of the sale and the sales amount for each product category. The data is preprocessed and transformed into a time series format to prepare it for forecasting.

**Notebook Contents**

The Jupyter Notebook is divided into several sections, each representing a step in the sales forecasting process:

1. Data Wrangling: In this section, the dataset is loaded into the notebook, and data cleaning techniques are applied. Unnecessary columns are dropped, and the data is sorted and grouped by date to obtain monthly mean sales data.

2. Time Series Forecasting: Using Facebook Prophet, a powerful time series forecasting library, separate models are built for each product category (furniture, office supplies, and technology sales). Prophet handles trend, seasonality, and holidays in time series data.

3. Forecast Visualization: The forecasted sales values for each product category are visualized using matplotlib. The forecasted values are plotted along with the actual sales data to visualize the model's performance.

4. Interpretation: The forecasted results are interpreted, including the trend, seasonality, and uncertainty intervals (yhat_lower and yhat_upper).

5. Integration: The forecasted results for furniture, office supplies, and technology sales are integrated into a single plot with subplots for each category to provide a clear view of the forecasted sales.

**Dependencies**

To run the notebook, you need to have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- fbprophet

**Usage**

To use this repository, simply download the Sales_Forecasting.ipynb notebook and the dataset file. Then, open the notebook in Jupyter and execute the cells in order to perform sales forecasting for the retail store.


**Acknowledgments**

This project is for educational purposes and is inspired by the time series forecasting research in the retail domain. Special thanks to the creators and contributors of the libraries used in this project.

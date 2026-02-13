# TASK-16-FORECASTING-TIME-SERIES-TREND-PREDICTION
Step 1 – Load dataset and convert dates
The dataset is imported and date columns are converted into proper datetime format. This ensures time-based operations like grouping and forecasting work correctly.
Step 2 – Aggregate sales by month/week
Sales values are grouped by monthly and weekly periods. This reveals overall patterns and prepares the data for trend analysis.
Step 3 – Plot sales trend over time
Line charts are created to visualize sales progression. These plots highlight growth, decline, or fluctuations across months and weeks.
Step 4 – Check seasonality with rolling mean
A rolling mean smooths the data to expose recurring seasonal patterns. This helps identify cycles that repeat over fixed intervals.
Step 5 – Split data into train/test by time
Data is divided chronologically into training and testing sets. This simulates real forecasting by ensuring the model learns from past and predicts future.
Step 6 – Fit forecasting models
Moving Average and Exponential Smoothing models are applied. These provide baseline and trend-sensitive forecasts for the sales data.
Step 7 – Predict next period sales
The fitted model generates a forecast for the upcoming period. This prediction is plotted alongside historical data for clarity.
Step 8 – Compute error metrics
MAE and MAPE are calculated to measure forecast accuracy. These metrics quantify how close predictions are to actual sales.
Step 9 – Export forecast results
Final results including actuals and forecasts are saved to a CSV file. This makes the output reusable for reporting or further analysis.

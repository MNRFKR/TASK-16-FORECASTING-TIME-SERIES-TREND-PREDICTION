# TASK-16-FORECASTING-TIME-SERIES-TREND-PREDICTION
Step 1 – Load dataset and convert dates
The dataset is imported into the environment, and date columns are converted into proper datetime format. This ensures accurate handling of time-based operations.
Step 2 – Aggregate sales by month/week
Sales are grouped by monthly and weekly intervals. This aggregation reveals overall performance trends and prepares the data for analysis.
Step 3 – Plot sales trend over time
Visualizations are created to show how sales evolve across months and weeks. These plots highlight growth patterns, declines, and fluctuations.
Step 4 – Check seasonality with rolling mean
A rolling mean smooths the data to uncover recurring seasonal cycles. This helps identify predictable patterns that repeat over fixed intervals.
Step 5 – Split data into train/test by time
Data is divided chronologically into training and testing sets. This simulates real forecasting by ensuring the model learns from past data and predicts future outcomes.
Step 6 – Fit forecasting models
Moving Average and Exponential Smoothing models are applied to the aggregated sales. These provide baseline and trend-sensitive forecasts.
Step 7 – Predict next period sales
The fitted model generates a forecast for the upcoming period. This prediction is plotted alongside historical data for clarity and comparison.
Step 8 – Compute error metrics
MAE and MAPE are calculated to measure forecast accuracy. These metrics quantify how close predictions are to actual sales values.
Step 9 – Export forecast results
Final results, including actuals and forecasts, are saved into a CSV file. This makes the output reusable for reporting and further analysis.

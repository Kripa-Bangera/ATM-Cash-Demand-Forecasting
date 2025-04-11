# H1**🏧 ATM Cash Demand Forecasting**

This project focuses on forecasting ATM cash demand using real-world data from the Reserve Bank of India (RBI). We developed and compared three time series models to accurately predict future cash requirements:
1.Exponential Smoothing
2.SARIMA (Seasonal ARIMA)
3.Dynamic Harmonic Regression (DHR)
#### H4The DHR model demonstrated the best performance in terms of RMSE.

### H3📊 Objective
Efficiently forecasting ATM cash withdrawals is crucial for optimal currency logistics. This project aims to:
-Minimize cashouts and overstocking.
-Improve operational efficiency.
-Enhance customer satisfaction.

### H3🧠 Methodology
1.Data Preprocessing
-Cleaning and formatting RBI transaction data.
-Visualizing trends and seasonality.

2.Modeling Approaches
-Simple Exponential Smoothing
-SARIMA
-DHR with seasonal regressors

3.Model Evaluation
-Root Mean Square Error (RMSE) used to compare models.

### H3📈 Model Comparison
Model	RMSE:-
-Exponential Smoothing - 791.35
-SARIMA	- 610.92
-DHR- 510.73
✅ DHR outperformed the other models.

### H3🛠 Tools Used
-Python (Jupyter Notebook)
-pandas, numpy, matplotlib, seaborn
-statsmodels, pmdarima
-scikit-learn

### H3📌 Conclusion
By leveraging time series models, particularly DHR, we were able to generate accurate forecasts for ATM cash demand using actual RBI data—highlighting the importance of choosing the right model based on data characteristics.

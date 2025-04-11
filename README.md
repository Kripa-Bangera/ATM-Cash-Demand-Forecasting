# **🏧 ATM Cash Demand Forecasting**

This project focuses on forecasting ATM cash demand using real-world data from the Reserve Bank of India (RBI). We developed and compared three time series models to accurately predict future cash requirements:
1. Exponential Smoothing
2. SARIMA (Seasonal ARIMA)
3. Dynamic Harmonic Regression (DHR)
#### The DHR model demonstrated the best performance in terms of RMSE.

## 📄Dataset
The dataset used in this project was sourced from the Reserve Bank of India (RBI)'s official website.

[Click here to access the dataset] (https://www.rbi.org.in/Scripts/BS_PressReleaseDisplay.aspx?prid=49901)


### 📊 Objective
Efficiently forecasting ATM cash withdrawals is crucial for optimal currency logistics.  
This project aims to:  
- Minimize cashouts and overstocking  
- Improve operational efficiency  
- Enhance customer satisfaction  

### 🧠 Methodology
1.Data Preprocessing
- Cleaning and formatting RBI transaction data.
- Visualizing trends and seasonality.

2.Modeling Approaches
- Simple Exponential Smoothing
- SARIMA
- DHR with seasonal regressors

3.Model Evaluation
- Root Mean Square Error (RMSE) used to compare models.

### 📈 Model Comparison
Model	RMSE:-
- Exponential Smoothing - 791.35
- SARIMA	- 446.21
- DHR- 402.22
✅ DHR outperformed the other models.

### 🛠 Tools Used
- Python (Jupyter Notebook)
- pandas, numpy, matplotlib, seaborn
- statsmodels, pmdarima
- scikit-learn

### 📌 Conclusion
By leveraging time series models, particularly DHR, we were able to generate accurate forecasts for ATM cash demand using actual RBI data—highlighting the importance of choosing the right model based on data characteristics.

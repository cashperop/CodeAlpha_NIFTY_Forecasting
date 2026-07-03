# NIFTY 50 Forecasting using ARIMAX-GARCH-EGARCH Models

Project Overview
This project focuses on forecasting the NIFTY 50 index using ARIMAX, GARCH, and EGARCH models. Historical financial and macroeconomic data were collected, cleaned, analyzed, and used to build forecasting models.


Project Structure

1. dataextract.ipynb
This notebook contains the Python code used for data collection.
- Data was collected using the Python `yfinance` library.
- Historical data for NIFTY 50, S&P 500, Crude Oil, USD/INR, and other variables were extracted.
- Data extraction and initial preprocessing were performed using Python.



2. combined collected data.xlsx
This file contains the complete raw dataset collected from multiple sources.
- Data collected using Python (`yfinance`).
- Some variables were collected manually from official sources where automated extraction was not possible (e.g., RBI and other government/economic websites).
- All collected datasets were combined into a single file.


3. ANALYSIS 4.xlsx
This file contains the processed and transformed dataset used for analysis.
The following preprocessing steps were performed:
- Handling missing values
- Data cleaning
- Data transformation
- Log transformation
- Variable selection
- Data preparation for time series analysis



4. Analysis.ipynb
This notebook contains the complete statistical and econometric analysis:
- Correlation Analysis
- Multicollinearity Check (VIF)
- Stationarity Tests (ADF and KPSS)
- CUSUM Test
- ACF and PACF Analysis
- ARIMAX Modeling
- GARCH Modeling
- EGARCH Modeling
- Model Diagnostics
- Forecasting and Performance Evaluation



5. VISUALIZATION Folder
This folder contains all graphs and visualizations generated during the analysis:
- Time Series Plot
- Rolling Mean and Rolling Standard Deviation
- Correlation Matrix
- ACF Plot
- PACF Plot
- Volatility Clustering Plot
- Conditional Volatility Plot
- Forecast Comparison Plot
- Actual vs Predicted NIFTY Plot



6. Tools and Libraries Used
- Python
- Google Colab
- yfinance
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- ARCH package
- Microsoft Excel



# Model Performance
Best Model: ARIMAX + EGARCH (Student's t Distribution)

Forecast Accuracy:
- MAE: ₹568.04
- RMSE: ₹607.37
- MAPE: 2.17%

---


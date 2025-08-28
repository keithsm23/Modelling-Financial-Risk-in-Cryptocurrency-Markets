# Modelling Financial Risk in Cryptocurrency Markets

This repository contains the code for my MSc Data Science project **“Modelling Financial Risk in Cryptocurrency Markets”**. The goal is to compare a point-forecasting LSTM (Long Short Term Memory) approach with a GARCH (Generalized Autoregressive Conditional Heteroskedasticity) volatility model and to investigate whether UK inflation adds predictive value to BTC forecasts.

## Contents
- Modelling_Financial_Risk_in_Cryptocurrency_Markets.ipynb: Main notebook with preprocessing, neural network training, and GARCH analysis.
- BTC_GBP_Historical_Data.xlsx: The cryptocurrency price data (or mention external source if too large).
- Inflation_data.csv: The inflation data 
- plots/: Folder with training graphs and GARCH outputs.
- Keith_23034718_Final_Project_Report.pdf: Final report.

## Requirements
To run the code, you need the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow or keras
- arch (for GARCH modeling)

You can install them using:
bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow arch.

## How to use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/crypto-risk-modelling.git
Open the Jupyter notebook and run it step-by-step.
Modify paths to match your local dataset if necessary.

## Models Used
LSTM(Long Short Term Memory) 
GARCH(Generalized Autoregressive Conditional Heteroskedasticity)

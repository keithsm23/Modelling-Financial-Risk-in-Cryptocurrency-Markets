# Modelling Financial Risk in Cryptocurrency Markets

This repository contains the code for my MSc Data Science project **“Modelling Financial Risk in Cryptocurrency Markets”**. The goal is to compare a point-forecasting LSTM (Long Short Term Memory) approach with a GARCH (Generalized Autoregressive Conditional Heteroskedasticity) volatility model and to investigate whether UK inflation adds predictive value to BTC forecasts.

## Contents
- Modelling_Financial_Risk_in_Cryptocurrency_Markets.ipynb: Main notebook with preprocessing, neural network training, and GARCH analysis.
- BTC_GBP_Historical_Data.xlsx: The cryptocurrency price data (or mention external source if too large).
- Inflation_data.csv: The inflation data 
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
How to Use
To get a local copy of the project up and running on your machine, please follow these simple steps.

Clone the Repository
Use the command below to download the project to your computer.

bash
git clone https://github.com/your-username/Modelling-Financial-Risk-in-Cryptocurrency-Markets.git  

Replace your-username with your actual GitHub username.

Navigate to the Project Directory
Change your current directory to the project folder.

bash
cd Modelling-Financial-Risk-in-Cryptocurrency-Markets
Install Dependencies
Install the required Python libraries listed in the requirements.txt file.

bash
pip install -r requirements.txt
Run the Jupyter Notebook
Launch Jupyter Notebook to open and execute the analysis.

bash
jupyter notebook
Once Jupyter is running in your browser, open the file Crypto_Risk_Modelling_Analysis.ipynb (or your main notebook's filename) and run the cells sequentially.

Note: The notebook will attempt to load the dataset from the specified path in the code (e.g., data/BTC_GBP_and_UK_inflation.csv). Please ensure you have the dataset in the correct location or update the file path in the notebook accordingly.



## Data Sources

## Bitcoin Daily Prices
- Source: Yahoo Finance ([https://finance.yahoo.com/quote/BTC-USD/history)](https://finance.yahoo.com/quote/BTC-GBP/history/?filter=history&frequency=1d&period1=1594771200&period2=1752537600))
- Frequency: Daily
- Variables: Date, Open, High, Low, Close, Adj Close, Volume
- Licence: Free to use for academic purposes (attribution recommended).

## UK Inflation (CPI)
- Source: Office for National Statistics ([https://www.ons.gov.uk/economy/inflationandpriceindices](https://www.ons.gov.uk/economy/inflationandpriceindices/timeseries/l55o/mm23))
- Frequency: Monthly (converted to match daily BTC series by forward filling).
- Variables: CPI % annual change.
- Licence: Open Government Licence v3.0 (you are free to use, attribution required).


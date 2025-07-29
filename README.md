# Modelling Financial Risk in Cryptocurrency Markets

This repository contains code for my MSc Data Science final project. The goal of this project is to model and analyze financial risk in the cryptocurrency markets using deep learning and econometric models like GARCH.

## Contents
- Modelling_Financial_Risk_in_Cryptocurrency_Markets.ipynb: Main notebook with preprocessing, neural network training, and GARCH analysis.
- GBP.csv: The cryptocurrency price data (or mention external source if too large).
- Inflation.csv: The inflation data 
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

# How to use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/crypto-risk-modelling.git
Open the Jupyter notebook and run it step-by-step.

Modify paths to match your local dataset if necessary.

# Models Used
Neural Network (Keras) for binary classification of returns.

GARCH(1,1) model for volatility prediction.

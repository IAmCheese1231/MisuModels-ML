# MisuModels-ML

This code is a predictive software, running a sophisticated ensemble model 
with advanced backtesting to make real-time predictions. It takes in user-inputted
parameters for the model to grow off of, and allows for grpahical and numerical analysis
of each model results.

The model uses a weighted combination of Random Forest, Gradient Boosting, and Ridge Regression
to formulate its final predictions. Employing over 40 technical indicators, the code conducts
automated selection of indicators with backtesting and dynamic retraining.

The GUI allows for the user to input various parameters of the model, and then outputs 4 key graphs
depicting model performance measurements, alongside numerical historical gains. Then, it
caches the model to offer a within 30 day prediction of the stock.

## Files Description

- `main.py` - Generates the GUI. Run this to activate the model.
- `backtest.py` - Transmits the user-entered data from the GUI into core_model.
- `core_model.py` - Contains code retraining the ensemble model, with also backtesting.

## Installation

Run 

pip install -r requirements.txt

to install all the key requirements for this code to work. 
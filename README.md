# Stock Price Prediction with Deep Learning

## Project Overview

This repository contains a stock price prediction project using deep learning. The project includes:

- `data_preparation.ipynb` - data loading, cleaning, and preparation.
- `helper_functions.ipynb` - reusable preprocessing, scaling, and sequence utilities.
- `lstm_training.ipynb` - training and evaluating an LSTM model.
- `transformer_training.ipynb` - training and evaluating a Transformer model.

The notebooks demonstrate how to transform historical stock data into time series sequences and train models to forecast future closing prices.

## How to Clone the Repository

Open a terminal and run:

```powershell
git clone https://github.com/aashixh0/Stock-Price-Prediction>
cd "Stock Price Prediction"
```

## Create and Use the Virtual Environment

From the repository root, create the `myenv` virtual environment:

```powershell
python -m venv myenv
```

Activate the environment in PowerShell:

```powershell
myenv\Scripts\Activate
```

Or activate it in Command Prompt:

```cmd
myenv\Scripts\activate.bat
```

Once the environment is active, install the required packages:

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Running the Notebooks

With the virtual environment active and dependencies installed:

```powershell
jupyter notebook
```

Then open the notebooks in this order:

1. `data_preparation.ipynb`
2. `helper_functions.ipynb`
3. `lstm_training.ipynb`
4. `transformer_training.ipynb`

## Repository Structure

- `data_preparation.ipynb` - prepare and transform raw stock price data.
- `helper_functions.ipynb` - reusable helper functions for preprocessing and visualization.
- `lstm_training.ipynb` - LSTM-based model training and evaluation.
- `transformer_training.ipynb` - Transformer-based model training and evaluation.
- `datasets/` - optional folder for saved data files.
- `requirements.txt` - list of Python packages required for the notebooks.

## Notes

- The notebooks use historical stock price data, typically downloaded from Yahoo Finance.
- `requirements.txt` includes the main dependencies needed to run the notebooks.
- If the dataset is not already available, the notebooks should download it automatically when run.

## Recommended Workflow

1. Clone the repository.
2. Create and activate `myenv`.
3. Install dependencies from `requirements.txt`.
4. Launch Jupyter Notebook.
5. Run `data_preparation.ipynb` first, then `helper_functions.ipynb`, followed by the training notebooks.

## Optional Improvements

- Add technical indicators such as volume, moving averages, RSI, or MACD.
- Use multivariate inputs for richer forecasting.
- Tune model hyperparameters for better performance.
- Compare results across different stock tickers.

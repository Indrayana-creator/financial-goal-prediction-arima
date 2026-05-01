# Financial Goal Prediction System using ARIMA

This project is a web-based financial tracking and forecasting system built using Flask. It helps users manage their income and expenses while predicting future savings using time series forecasting.

## Features
- Track income and expenditure history
- Store financial records in a database
- Perform time series forecasting using ARIMA model
- Visualize financial trends and predictions
- Provide insights to support financial planning

## Model Overview
This project uses the ARIMA (AutoRegressive Integrated Moving Average) model to forecast future financial trends based on historical data. The model analyzes patterns in income and expenditure data to estimate future savings and support better financial decision-making.

## Tech Stack
- Python
- Flask
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- SQLite

## Project Workflow
1. User inputs financial data (income and expenses)
2. Data is stored in a database
3. Data is cleaned and prepared for analysis
4. ARIMA model is applied to perform forecasting
5. Results are visualized to provide insights

## How to Run the Project

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/financial-goal-prediction-arima.git
cd financial-goal-prediction-arima
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run Application
```bash
python app.py
```
### 4. Open in Browser
```bash
http://127.0.0.1:5000/
```

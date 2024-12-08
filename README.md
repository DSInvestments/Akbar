Enhanced Stock Predictor
Author: Dhruv Shajikumar
Date: December 6, 2024

Overview
The Enhanced Stock Predictor is a comprehensive Python-based application designed to predict stock prices using historical data. It leverages Alpaca's API to fetch minute-level stock data, applies advanced preprocessing and feature engineering techniques, and utilizes a Transformer-based neural network for accurate predictions. The project also includes real-time updates, progress indicators, and detailed evaluations to ensure transparency and reliability.

Features
Data Acquisition: Fetches approximately one year of historical stock data at 1-minute intervals for multiple symbols using Alpaca's API.
Advanced Preprocessing: Implements data cleaning, handling missing values, and normalizing features.
Feature Engineering: Creates a wide range of technical indicators and lag features to enhance model performance.
Transformer-Based Model: Utilizes a sophisticated Transformer architecture optimized for time-series forecasting.
Hyperparameter Optimization: Employs Optuna for efficient hyperparameter tuning to achieve optimal model performance.
Comprehensive Evaluation: Calculates various performance metrics including MSE, MAE, RMSE, R², MAPE, and more.
Visualization: Generates insightful plots for actual vs. predicted prices, residuals, cumulative returns, and more.
Model Explainability: Integrates SHAP for interpreting model predictions and understanding feature importance.
Real-Time Updates: Provides real-time logging and progress indicators to monitor execution.
Technologies Used
Python Libraries:
numpy, pandas: Data manipulation and analysis.
matplotlib, seaborn: Data visualization.
scipy: Scientific computing.
torch (PyTorch): Deep learning framework.
scikit-learn: Machine learning utilities.
statsmodels: Statistical modeling.
optuna: Hyperparameter optimization.
shap: Model explainability.
joblib: Model serialization.
alpaca-trade-api: Accessing Alpaca's trading API.
python-dotenv: Managing environment variables.
tqdm: Progress bars.

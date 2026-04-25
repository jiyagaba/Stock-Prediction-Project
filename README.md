📈 NIFTY 50 Stock Price Prediction & Analysis
A Machine Learning Approach to Financial Forecasting

🎓 Project Overview
Hi there! This project is my deep dive into the world of Quantitative Finance and Machine Learning. My goal was to see if I could accurately predict the closing prices of NIFTY 50 stocks by comparing traditional statistical methods against modern deep learning architectures.

Through this project, I performed extensive Exploratory Data Analysis (EDA), engineered over 20 technical indicators, and benchmarked 10+ different models to find the "sweet spot" for short-term market forecasting.

🛠️ The Toolkit
Data Source: yfinance API (Real-time & Historical Yahoo Finance data)

Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly (for interactive charts)

Machine Learning: Scikit-Learn, XGBoost, Prophet

Deep Learning: TensorFlow / Keras (LSTM)

Technical Analysis: ta library

🚀 Methodology: How I Built It
1. Data Prep & "Cleaning the Noise"
Financial data is messy. I pulled daily OHLCV data for the NIFTY 50 and handled missing values and outliers to ensure the models wouldn't get confused by "bad" data.

2. Feature Engineering (The Secret Sauce)
Raw price isn't enough. I built custom features to give the models more context:

Momentum: RSI, MFI, and customized Momentum lags.

Trend: SMA/EMA crossovers and MACD.

Volatility: Bollinger Bands and ATR.

Candlestick Patterns: Intraday ranges and shadow analysis.

3. Model Training & Tournament
I didn't just pick one model; I held a "tournament" to see which performed best:

Baselines: Naive Forecast, Linear/Ridge Regression.

Non-Linear: KNN, SVR, and Random Forest.

Boosting Giants: XGBoost and Gradient Boosting.

Time-Series Specialists: ARIMA, Facebook Prophet, and LSTM (Long Short-Term Memory) neural networks.

The Powerhouse: An Ensemble Model combining the top performers.

📊 Evaluation: How I Measure Success
To keep myself honest, I evaluated every model using:

RMSE & MAE: To see how many Rupees the prediction was off by.

R² Score: To see how much of the "market wiggle" the model actually explained.

Directional Accuracy: (My favorite) Does the model at least get the direction (Up/Down) right?

 How to Run This
Clone the repo:

Bash
git clone https://github.com/yourusername/nifty50-prediction.git
Install the gear:

Bash
pip install -r requirements.txt
Launch the Notebook: Open Stock_Prediction.ipynb and run the cells.

Try your stock: When prompted, type in a ticker like RELIANCE.NS or INFY.NS to see the magic happen!

# 📈 Stock Price Prediction using Machine Learning

This project predicts the next day's stock closing price using historical stock data and machine learning.

### 🔧 How it Works
- Multiple CSV files are uploaded in a ZIP format.
- The data is extracted, cleaned, and merged using pandas.
- Only numeric columns are retained for model training.
- New features like lag values of the closing price are added.
- The target is the next day’s closing price (Close_next).

### 🧠 Model Used
We use HistGradientBoostingRegressor from scikit-learn for training. It handles numeric data efficiently and performs well for time series-like data.

### ⚙ Workflow
1. Upload ZIP with stock CSV files.
2. Automatically extract and combine data.
3. Clean and engineer features.
4. Split into training and testing sets.
5. Scale data and train the model.
6. Evaluate using MSE and R² score.
7. Visualize predictions vs actual values.

### 📊 Output
A graph shows how closely the model’s predictions match real stock prices, helping assess performance visually.

### 📁 Requirements
- Python, Pandas, NumPy, scikit-learn, Matplotlib
- Best run in Google Colab

> *Note*: This project is educational and not meant for real-world trading.

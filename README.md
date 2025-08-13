 💹 Task 002: Predict Future Stock Prices (Short-Term)

 📌 Objective
Use historical stock data to predict the next day's closing price using regression models.

---

 📂 Dataset Used
- Stock market data from Yahoo Finance via the `yfinance` library.
- Example stock: Apple (AAPL)
- Time period: 2020-01-01 to 2023-12-31.

---

 🛠 Steps Performed
1. Loaded historical data using `yfinance`.
2. Selected features: `Open`, `High`, `Low`, and `Volume`.
3. Created target variable: next day’s `Close` price.
4. Removed missing values.
5. Split data into training (80%) and testing (20%) sets.
6. Trained a Linear Regression model using Scikit-learn.
7. Predicted closing prices for the test set.
8. Plotted Actual vs Predicted closing prices.
9. Evaluated model performance using Mean Squared Error (MSE).

---

🤖 Model Applied
- Linear Regression (`sklearn.linear_model.LinearRegression`)

---

 📊 Key Findings
- The model captures the overall price trend but struggles with short-term fluctuations.
- MSE provides a numerical measure of prediction error.
- More advanced models (Random Forest, LSTM) could improve prediction accuracy.

---

🧰 Tools & Libraries
- Python (Pandas, NumPy)
- yfinance
- Scikit-learn
- Matplotlib

---

📅 **Internship Duration:** Month Year – Month Year  
💻 **Author:** Muhammad Mustaqeem Javed

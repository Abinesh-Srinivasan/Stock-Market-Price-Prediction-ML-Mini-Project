# 📈 Stock Market Price Prediction using Machine Learning  

## Project Overview  
This project focuses on predicting the **next day's stock closing price** using **Machine Learning models**. The dataset used is from **TCS (Tata Consultancy Services)** stock price history. Various regression models such as **Linear Regression, Random Forest, and XGBoost** are trained and evaluated to determine the best-performing model.

---

## 📌 Workflow of the Project  

### **1. Data Collection**  
- The dataset contains historical stock price data for **TCS**, including columns like **Date, Open, High, Low, Close, Volume, and Trades**.
- Data is obtained from **Kaggle**.

### **2. Data Preprocessing**  
- The **Date** column is converted to a datetime format and sorted in ascending order.
- Missing values (if any) are handled by appropriate imputation techniques.
- A new column, **Next_Close**, is created, which represents the next day's closing price for prediction.
- The dataset is split into **features (X)** and **target (y)**.

### **3. Model Training**  
Three different models are trained to predict stock prices:  
✅ **Linear Regression** - A simple model that fits a straight-line relationship.  
✅ **Random Forest Regressor** - An ensemble model that improves accuracy using multiple decision trees.  
✅ **XGBoost Regressor** - A highly optimized gradient boosting model designed for better performance.  

### **4. Model Evaluation**  
To evaluate model performance, the following metrics are used:  
- **Mean Absolute Error (MAE)** - Measures the average absolute difference between actual and predicted prices.  
- **Mean Squared Error (MSE)** - Penalizes larger errors by squaring the differences.  
- **Root Mean Squared Error (RMSE)** - A more interpretable metric showing actual price differences.  
- **R² Score** - Represents how well the model explains the variance in stock prices (closer to 1 is better).  

### **5. Results & Visualization**  
- **Comparison of Models:** A bar chart is used to visualize model performance based on R² scores.
- **Actual vs Predicted Prices:** A line graph compares real stock prices with the best model's predictions.
- The model with the highest R² score and lowest error is chosen as the best-performing model.

---

## 📊 Key Concepts  

### **📅 Time-Series Forecasting**  
- Since stock prices depend on historical trends, **time-series forecasting** methods are useful.
- More advanced techniques like **LSTM (Long Short-Term Memory)** can be explored for future improvements.

### **💪 Ensemble Learning**  
- Models like **Random Forest and XGBoost** leverage multiple weak learners to improve accuracy.
- Ensemble models typically perform better than simple linear models in complex datasets.

### **🔄 Feature Engineering**  
- Additional features like **Moving Averages, RSI (Relative Strength Index), Bollinger Bands** can further enhance predictions.
- However, in this project, only basic stock data is used for simplicity.

---

## 🏆 Final Outcome  
- **Best Performing Model:** ✅ **Linear Regression** (Highest R² score, lowest error).  
- **Observations:** Linear Regression handled stock price fluctuations better than traditional models.  
- **Next Steps:** Implement **LSTM models** and integrate **real-time stock data** for live predictions.  

---

## Conclusion  
This project successfully demonstrates how **Machine Learning models** can be used for **stock market price prediction**. While traditional regression models provide a good starting point, **advanced deep learning techniques** and **real-time data processing** can further enhance accuracy.


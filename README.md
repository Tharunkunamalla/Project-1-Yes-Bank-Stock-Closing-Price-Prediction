# Project-1-Yes-Bank-Stock-Closing-Price-Prediction

- 🧠 Problem Statement
  The main goal is to predict the monthly closing stock price of Yes Bank using time series or other predictive machine learning models based on historical stock data.
Project Objective:
- This project focuses on predicting the monthly closing stock price of Yes Bank using historical stock data to support financial decision-making and forecasting.

Dataset & Features:
- The dataset includes key financial indicators such as Open, High, Low, and Close prices on a monthly basis.

Data Preprocessing:
- Steps included converting the Date column to datetime, extracting Month and Year, creating a Volatility feature (High - Low), handling outliers using the IQR method, and scaling numerical features using StandardScaler.

Data Visualization:
- Exploratory Data Analysis was performed using Matplotlib and Seaborn, creating 13+ visualizations like line plots, boxplots, histograms, scatter plots, correlation heatmaps, and pair plots to uncover trends and relationships in the data.

Feature Engineering & Selection:
- Engineered new time-based and statistical features, eliminated low-value predictors, and retained meaningful ones such as Open, High, Low, Month, Year, and Volatility.

Model Building:
- Three regression models were implemented—Linear Regression, K-Nearest Neighbors (KNN), and XGBoost —using GridSearchCV for hyperparameter tuning and evaluated with cross-validation.

Evaluation Metrics:
- Models were assessed using MAE, MSE, and R², where Linear Regression achieved the best performance (MAE = 5.90, MSE = 84.02, R² = 0.9907), indicating a strong linear pattern.

Conclusion:
- The project concludes that Linear Regression is the most effective and interpretable model, providing highly accurate predictions with over 99% variance explained, making it ideal for supporting stock investment strategies and financial planning.

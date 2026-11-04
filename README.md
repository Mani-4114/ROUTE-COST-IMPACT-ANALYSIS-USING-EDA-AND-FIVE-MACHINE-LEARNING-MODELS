
# ✈️ Route Cost Impact Analysis Using EDA and Five Machine Learning Models

## 📌 Project Overview

This project focuses on analyzing airline ticket prices and predicting flight cancellations using Exploratory Data Analysis (EDA) and Machine Learning techniques.

The project implements one regression model for ticket price prediction and four classification models for flight cancellation prediction.

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on airline data.
- Analyze ticket prices across different airlines and conflict phases.
- Perform data preprocessing and feature engineering.
- Predict total airline ticket prices.
- Predict flight cancellations using classification algorithms.
- Evaluate and compare machine learning models.
- Identify the best-performing classification model.

## 📂 Dataset Information

| Description | Value |
|---|---|
| Dataset | Airline Route Cost Dataset |
| Records | 3,132 |
| Columns | 25 |
| Missing Values | 0 |
| Duplicate Records | 0 |
| Cancelled Flights | 68 |
| Non-Cancelled Flights | 3,064 |
| Cancellation Rate | 2.17% |

### Important Features

- Month
- Conflict Phase
- Airline
- IATA Code
- Origin City
- Destination City
- Aircraft Type
- Route Distance
- Brent Crude Price
- Jet Fuel Price
- Total Ticket Price
- Flight Cancellation Status

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Exploratory Data Analysis (EDA)

The following analyses are performed:

- Dataset overview
- Statistical summary
- Missing value analysis
- Duplicate record detection
- Ticket price distribution
- Average ticket price by conflict phase
- Correlation analysis
- Actual vs Predicted ticket price visualization
- Classification model comparison
- Confusion matrix visualization

## ⚙️ Data Preprocessing

- Handling numerical and categorical features
- Median imputation for numerical variables
- Most frequent imputation for categorical variables
- Standardization using StandardScaler
- One-Hot Encoding for categorical variables
- Train-Test Split
- Stratified sampling for classification
- Prevention of data leakage

## 🤖 Machine Learning Models

### Regression Model

| Model | Purpose |
|---|---|
| Linear Regression | Predict total airline ticket price |

### Classification Models

| Model | Purpose |
|---|---|
| Logistic Regression | Predict flight cancellation |
| Decision Tree | Predict flight cancellation |
| K-Nearest Neighbors (KNN) | Predict flight cancellation |
| Random Forest | Predict flight cancellation |

## 📊 Model Evaluation Metrics

### Regression Metrics

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

### Classification Metrics

- Accuracy
- Balanced Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- PR-AUC
- Confusion Matrix

## 📈 Results

### Linear Regression

| Metric | Value |
|---|---:|
| MAE | 69.41 |
| MSE | 14,081.44 |
| RMSE | 118.67 |
| R² Score | 0.9168 |

The Linear Regression model explains approximately 91.68% of the variation in ticket prices.

### Classification Results

| Model | Accuracy | F1-Score | ROC-AUC | PR-AUC |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.9314 | 0.3175 | 0.9497 | 0.4575 |
| Decision Tree | 0.9282 | 0.3478 | 0.9081 | 0.3106 |
| KNN | 0.9761 | 0.2105 | 0.8326 | 0.2645 |
| Random Forest | 0.9474 | 0.3774 | 0.9691 | 0.4920 |

### 🏆 Best Classification Model

**Random Forest**

- Highest F1-Score: 0.3774
- Highest PR-AUC: 0.4920
- ROC-AUC: 0.9691

Random Forest is selected as the best classification model based on its F1-Score.

## 🚀 Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the Project Folder

```bash
cd YOUR-REPOSITORY
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells sequentially to perform data analysis, preprocessing, model training, and evaluation.

## 📌 Conclusion

This project demonstrates the application of Exploratory Data Analysis and Machine Learning in airline ticket price prediction and flight cancellation classification.

Linear Regression achieved an R² score of 0.9168 for ticket price prediction, while Random Forest achieved the highest F1-Score of 0.3774 among the classification models.

The project highlights the importance of evaluating classification models using appropriate metrics when dealing with imbalanced datasets.

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Classification threshold optimization
- Class imbalance handling
- Improved cancellation prediction
- Validation using newer airline datasets

## 👨‍💻 Author

**Dantla Manikanta Reddy**

B.Tech – Computer Science and Engineering  
Lovely Professional University

Student ID: 12403443

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Documentation](https://numpy.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---
⭐ If you find this project useful, consider giving it a star!

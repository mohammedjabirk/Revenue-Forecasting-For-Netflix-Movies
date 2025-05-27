
# 🎬 Netflix Movies Analysis and Prediction 

This project involves an in-depth analysis and prediction of Netflix movies using Machine Learning and Power BI. The goal is to explore the dataset, extract insights, and predict movie revenue using machine learning models.

## 📁 Files Included

- `Netflix_Movies (ML).ipynb` — Jupyter Notebook containing data preprocessing, visualization, model training, and evaluation.
- `Netflix Movies-Analysis-POWERBI.pbix` — Power BI report dashboard with key visuals and insights.

---

## 📊 Power BI Analysis

The Power BI report covers:

- **Genre distribution**
- **Revenue trends**
- **IMDb ratings overview**
- **Correlation between budget and revenue**
- **Top-performing movies and genres**
  
📈 Insights

- High-budget movies tend to have higher revenue, but not always.

- Certain genres consistently perform better.

- IMDb rating is moderately correlated with revenue.

- Power BI visuals provide quick access to top-performing movies.
---

## 🤖 Machine Learning Workflow (Jupyter Notebook)

The machine learning notebook includes the following stages:

1. Data Collection

* Dataset loaded from a CSV file (Netflix movie dataset).

* Contains features such as: Title, Genre, Release Date, Budget, Revenue, Runtime, IMDb Rating, etc.

2. Data Preprocessing (Jupyter Notebook)

* Missing Values: Handled via imputation or row removal.

* Data Types: Converted columns to appropriate types (datetime, float, etc.).

* Encoding: Applied one-hot or label encoding for categorical variables like Genre.

* Feature Selection: Chose important columns such as Budget, Runtime, Rating, etc., for prediction.

* Scaling: Normalized/standardized features for certain models.

3. Exploratory Data Analysis (EDA)

* Univariate Analysis: Distribution of genres, budgets, revenues, ratings.

* Bivariate Analysis: Revenue vs Budget, Rating vs Revenue.

* Correlation Matrix: Identified relationships between numerical features.

* Outlier Detection: Visualized using boxplots and histograms.

4. Model Building

* Train-Test Split: Split data into training and testing sets.

* Models Used:

* Linear Regression

* Random Forest Regressor
  
  (Optional: XGBoost, Decision Tree)

5. Model Evaluation:

* RMSE (Root Mean Square Error)

* MAE (Mean Absolute Error)

* R² Score

6. Prediction

* Predicted Revenue of movies based on features.

* Compared model performance and selected the best one.


---

## 📌 Technologies Used

- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Jupyter Notebook**
- **Power BI**
- **Machine Learning Models:** Linear Regression, Random Forest, etc.

---

## 🚀 How to Run

### 📌 For Jupyter Notebook:
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

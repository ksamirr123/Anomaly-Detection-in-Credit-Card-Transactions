# 💳 Credit Card Fraud Detection

This project is focused on detecting fraudulent credit card transactions using machine learning models. The dataset used is highly imbalanced, with very few fraud cases, making it a great challenge to work on.

## 📁 Dataset
The dataset is taken from [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and contains transactions made by European cardholders in September 2013.

- Rows: 284,807 transactions  
- Columns: 30 (includes anonymized features V1–V28, Time, Amount, and Class)

## ⚙️ Project Workflow

### 1. Data Collection
- Loaded the dataset using Pandas.
- Explored the basic structure and contents.

### 2. Data Cleaning
- Checked for missing values.
- Verified data types and structure.

### 3. Exploratory Data Analysis (EDA)
- Visualized class distribution.
- Plotted distributions of `Time` and `Amount`.
- Used heatmap to show feature correlations.

### 4. Model Training
Trained three models:
- Random Forest Classifier ✅
- Logistic Regression ✅
- (Incorrectly used) Decision Tree Regressor ❌

> Note: The regressor was included by mistake. It should be replaced with a classifier.

### 5. Evaluation
- Evaluated models using **accuracy score**.
- More metrics (precision, recall, F1-score) can be added for better insight.

## 📌 Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Future Improvements
- Use `DecisionTreeClassifier` instead of `DecisionTreeRegressor`.
- Add confusion matrix and classification report.
- Try techniques for handling imbalanced data like SMOTE.

## 📄 Project Status
✅ Completed initial version  
🛠️ Improvements to be made (evaluation & model replacement)

## 📬 Contact
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/) if you have any questions or suggestions!


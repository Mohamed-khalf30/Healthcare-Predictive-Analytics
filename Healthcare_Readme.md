# Healthcare Predictive Analytics

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-green)

## Project Overview
This project aims to develop a **Healthcare Predictive Analytics System** using machine learning techniques to classify breast cancer cases. The model assists healthcare professionals in making accurate diagnoses based on clinical data.

## Dataset
- **Source:** [Kaggle](https://www.kaggle.com/)
- **Preprocessing:**
  - Checked data types, null values, and duplicate records.
  - Addressed imbalanced data and dropped irrelevant columns.
  - Corrected inconsistencies in categorical variables.

## Exploratory Data Analysis (EDA)
- Generated **heatmaps** and **pie charts** to visualize feature correlations.
- Extracted meaningful insights to understand the relationships between key variables.
- Performed **feature encoding** using **OneHotEncoder** and **LabelEncoder**.

## Feature Selection
- Used **XGBoost** to extract the top 10 most important features.

## Model Training & Optimization
- **Tested multiple machine learning algorithms** and selected the best three models.
- **Hyperparameter tuning** performed using **Randomized Search** to optimize performance.
- **Final Model:** **SVC (Support Vector Classifier)** with the best parameters to prevent overfitting.

## Model Evaluation
- **Accuracy on Training Data:** 97.74%
- **Accuracy on Test Data:** 98.88%
- **Plotted ROC Curve** to validate model performance.

## Technologies Used
- **Programming Language:** Python
- **Libraries & Tools:**
  - Pandas, NumPy (Data Processing)
  - Seaborn, Matplotlib, Plotly Express (Data Visualization)
  - Scikit-Learn (Machine Learning)
  - XGBoost (Feature Selection & Model Training)

## Repository
Check out the full project on GitHub: [Healthcare Predictive Analytics](https://github.com/Mohamed-khalf30/Healthcare-Predictive-Analytics)

   pip install -r requirements.txt
   ```
3. Run the notebook to train and evaluate the model.

---
### 🔥 Feel free to contribute or raise issues! 🚀

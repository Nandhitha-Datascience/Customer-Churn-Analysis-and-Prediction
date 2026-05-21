# Customer Churn Analysis and Prediction

## Project Overview
This project analyzes customer churn behavior using Exploratory Data Analysis (EDA) and Machine Learning techniques. The goal of the project is to identify factors affecting customer churn and build a predictive model to classify churned customers.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Train-Test Split
6. Random Forest Model Building
7. Model Evaluation

## Data Preprocessing
- Converted TotalCharges column to numeric datatype
- Handled missing values using median imputation
- Removed unnecessary columns such as customerID
- Encoded categorical variables using pd.get_dummies()

## Exploratory Data Analysis
The project analyzed:
- Customer churn distribution
- Monthly charges vs churn
- Contract type vs churn
- Customer behavior patterns

## Machine Learning Model
Random Forest Classifier was used for customer churn prediction.

## Model Evaluation
The model was evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

## Key Insights
- Customers with month-to-month contracts showed higher churn rates
- Higher monthly charges were associated with increased churn
- Long-term contracts improved customer retention

## Conclusion
This project demonstrates the use of data analysis and machine learning techniques to predict customer churn and generate business insights for customer retention strategies.

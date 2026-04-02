# Customer Churn Prediction using Machine Learning

## Project Overview
This project focuses on predicting customer churn using machine learning techniques.  
Customer churn refers to customers who stop using a company's services.  
The goal is to analyze customer behavior and build a model to identify customers likely to churn.

---

## Dataset Information
The dataset contains 7043 customer records with 21 features, including:

- Customer demographics (gender, senior citizen, partner, dependents)
- Account information (tenure, contract type, payment method)
- Services used (internet service, online security, streaming, etc.)
- Billing details (monthly charges, total charges)
- Target variable: Churn (Yes/No)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Data Preprocessing (Encoding and Scaling)  
6. Model Building  
7. Model Evaluation  

---

## Data Preprocessing

- Converted TotalCharges to numeric  
- Handled missing values  
- Dropped unnecessary column (customerID)  
- Encoded categorical variables using one-hot encoding  
- Scaled numerical features  

---

## Machine Learning Models

- Logistic Regression  
- Random Forest Classifier  

---

## Model Performance

- Logistic Regression Accuracy: depends on execution  
- Random Forest Accuracy: higher compared to Logistic Regression  

Evaluation Metrics:
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## Key Insights

- Customers with month-to-month contracts are more likely to churn  
- Higher monthly charges increase churn probability  
- Customers with longer tenure are less likely to churn  
- Lack of tech support and online security increases churn risk  

---

## Conclusion

The project successfully predicts customer churn using machine learning models.  
It provides valuable insights that can help businesses improve customer retention strategies.

---

## Future Improvements

- Use advanced models such as XGBoost or deep learning  
- Perform hyperparameter tuning  
- Deploy the model using Flask or Streamlit  

---

## Project Structure

customer-churn-prediction/
│
├── churn_analysis.ipynb  
├── dataset.csv  
├── README.md  

---

## Author

Karthikadevi O  
Aspiring Data Scientist  

---

## Note

If you find this project useful, consider giving it a star on GitHub.

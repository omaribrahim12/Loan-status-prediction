# Loan-status-prediction


This project involves the analysis of a dataset obtained from Kaggle.com using various Python libraries, including NumPy, Pandas, Seaborn, and Scikit-Learn. The main goal is to create a machine learning model to predict a certain outcome from the dataset. Here's an overview of the steps I followed:

## Data Source
I acquired the dataset from Kaggle.com. It contains [ Loan_ID	Gender	Married	Dependents	Education	Self_Employed	ApplicantIncome	CoapplicantIncome	LoanAmount	Loan_Amount_Term	Credit_History	Property_Area	Loan_Status].

## Data Preprocessing
1. Removed Missing Values: I started by preprocessing the data, removing any rows or columns with missing (NaN) values to ensure data quality and consistency.

2. Data Insights: After cleaning the dataset, I conducted exploratory data analysis (EDA) to gain insights into the data's characteristics. I created visualizations using Seaborn to better understand the distribution of the data and relationships between variables.

3. Data Encoding: To utilize machine learning algorithms, I converted categorical string data into numerical values using techniques such as one-hot encoding or label encoding.

## Model Building
1. Train-Test Split: I split the dataset into a training set and a test set to evaluate the model's performance. This helps prevent overfitting and assess generalization.

2. SVM Model: For this project, I chose to implement a Support Vector Machine (SVM) classifier from Scikit-Learn. SVM is a powerful algorithm for classification tasks and often provides accurate results.

3. Model Evaluation: To assess the model's performance, I used the `accuracy_score` metric, which measures the proportion of correctly classified instances in the test set.

## Results
I have achieved an accuracy score of 0.83 with my SVM model, demonstrating the model's effectiveness in making predictions on this dataset.

This README provides an overview of the steps and processes involved in this project. You can explore the code and detailed analysis in the Jupyter Notebook provided in this repository.

Feel free to contact me if you have any questions or need further information.

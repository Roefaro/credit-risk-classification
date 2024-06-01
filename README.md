# Case Study: Credit Risk Classification with Logistic Regression

## Overview of the Analysis

This project aims to evaluate the creditworthiness of borrowers using a logistic regression model. The model is trained on a dataset of historical lending activity from a peer-to-peer lending services company. By analyzing various features of the loans, the model predicts whether a loan is healthy or poses a high risk of default.

## Project Details

**Project Title:** Credit Risk Classification

**Repository:** [credit-risk-classification](https://github.com/your-repo/credit-risk-classification)

**Data Source:** Historical lending activity data from a peer-to-peer lending services company.

**Objective:** To build and evaluate a logistic regression model to classify loans as either healthy or high-risk.

## Instructions Followed

### 1. Repository Setup
- Created a new repository named `credit-risk-classification`.
- Cloned the repository to the local machine.
- Created a folder titled `Credit_Risk` within the repository.
- Added the `credit_risk_classification.ipynb` and `lending_data.csv` files to the `Credit_Risk` folder.
- Pushed the initial changes to GitHub.

### 2. Data Preparation

#### a. Loading the Data
- Loaded the `lending_data.csv` file into a Pandas DataFrame.

#### b. Creating Feature and Label Sets
- Created the labels set (y) from the `loan_status` column.
  - Value `0`: Healthy loan.
  - Value `1`: High-risk loan.
- Created the features DataFrame (X) from the remaining columns.

#### c. Splitting the Data
- Split the data into training and testing sets using `train_test_split`.

### 3. Model Training and Evaluation

#### a. Training the Model
- Trained a logistic regression model using the training data (`X_train` and `y_train`).

#### b. Making Predictions
- Used the trained model to make predictions on the testing data (`X_test`).

#### c. Evaluating the Model
- Generated a confusion matrix.
- Printed the classification report.

## Results

The logistic regression model's performance was evaluated using the following metrics:

- **Accuracy Score:** 
- **Precision Score:** 
- **Recall Score:** 

### Model Performance

- **Accuracy Score:** Indicates the proportion of true results (both true positives and true negatives) among the total number of cases examined.
- **Precision Score:** Indicates the proportion of positive identifications that were actually correct.
- **Recall Score:** Indicates the proportion of actual positives that were identified correctly.

### Summary

The logistic regression model's performance metrics suggest that it can reasonably predict both healthy loans and high-risk loans. However, the precision and recall scores should be closely examined to understand the model's effectiveness in minimizing false positives and false negatives.

- **Recommendation:** Based on the model's performance, it can be recommended for use with caution. It is crucial to further refine the model and potentially explore other classification algorithms to improve prediction accuracy and reliability. If the model does not meet the company's standards for accuracy, additional data preprocessing and feature engineering may be necessary.

## Resources

- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Stack Overflow](https://stackoverflow.com/)
- [Previous Assignments and Course Material](#)

---

### Instructions for Running the Notebook

1. **Clone the Repository:** 
   ```bash
   git clone https://github.com/your-repo/credit-risk-classification.git
   cd credit-risk-classification/Credit_Risk
   ```

2. **Install Dependencies:** 
   ```bash
   pip install pandas scikit-learn
   ```

3. **Run the Notebook:**
   Open `credit_risk_classification.ipynb` in Jupyter Notebook or JupyterLab and execute the cells.

### Conclusion

This project demonstrates the use of logistic regression for credit risk classification. The model's performance metrics provide insights into its accuracy and reliability, helping the peer-to-peer lending services company make informed decisions about loan approvals and risk management.

---

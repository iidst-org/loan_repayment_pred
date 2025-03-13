# Loan Data Classification

## Overview
This project involves analyzing and classifying loan data using a Decision Tree model. The dataset includes various attributes related to loan applications, and the goal is to predict whether a loan will be repaid or not.

## Dataset
The dataset used in this project contains the following features:
- **Loan_ID**: Unique identifier for each loan
- **Gender**: Male/Female
- **Married**: Marital status of the applicant
- **Dependents**: Number of dependents
- **Education**: Education level of the applicant
- **Self_Employed**: Whether the applicant is self-employed
- **ApplicantIncome**: Monthly income of the applicant
- **CoapplicantIncome**: Monthly income of the co-applicant
- **LoanAmount**: Loan amount applied for
- **Loan_Amount_Term**: Term of the loan in months
- **Credit_History**: Record of past credit history (1 = good, 0 = bad)
- **Property_Area**: Urban, Semiurban, or Rural
- **Loan_Status**: Target variable (Y = Approved, N = Not Approved)

## Project Steps
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Standardizing numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and relationships
   - Checking for data imbalances

3. **Model Building**
   - Splitting data into training and testing sets
   - Training a Decision Tree classifier
   - Evaluating model performance using accuracy and confusion matrix

## Dependencies
To run this project, install the following Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Running the Notebook
1. Clone this repository:
   ```bash
   git clone <repo-link>
   cd loan-data-classification
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook loan_classification.ipynb
   ```

## Results
- The Decision Tree model provides insights into the key factors affecting loan approval.
- Performance metrics such as accuracy, precision, recall, and F1-score are analyzed.
- Further improvements can be made using hyperparameter tuning and ensemble methods.

## Future Enhancements
- Implementing advanced models like Random Forest, XGBoost, or Neural Networks.
- Feature engineering to improve model accuracy.
- Deploying the model using Flask or FastAPI.



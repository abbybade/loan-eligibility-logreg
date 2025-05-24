## Loan Eligibility Prediction Using Logistic Regression

This project automates the loan eligibility evaluation process for **Dream Housing Finance** using **logistic regression**. The solution analyzes customer **demographic** and **financial** data to predict whether a loan should be approved, streamlining decision-making and highlighting key eligibility factors.


### **Project Overview**

- **Objective**: Predict loan approval (`Loan_Status`) based on features like **income**, **loan amount**, **credit history**, **property area**, and more.  
- **Dataset**: `loan-test.csv` contains historical customer loan application data.  
- **Notebook**: All scripts, visualizations, modeling, and results are consolidated in `Project_Craft.ipynb`.


### **Features**

- **Exploratory Data Analysis (EDA)**: Visual comparisons between loan status and key features using **boxplots** and **stacked bar charts**.  
- **Data Preprocessing**:
  - Handling **missing values**
  - **Label encoding** & **one-hot encoding** for categorical features
  - **Standardization** of numerical features  
- **Feature Importance**: Assessed using **Random Forest** to guide feature selection.  
- **Modeling**:
  - **Logistic Regression** using a pipeline (**scikit-learn**)  
  - **Train-test split** (80-20)  
  - Evaluation using **accuracy**, **precision**, **recall**, and **F1-score**  
- **Future Extensions**: Additional models like **Decision Trees** or **Random Forests** can be used for performance benchmarking.

### **Key Results**

- `Credit_History` emerged as the **most important feature** for predicting loan approval.  
- **Logistic regression** provided a **balanced** and **interpretable** model for binary classification.


### **Files Included**

- `Project_Craft.ipynb`: Main notebook with all **code**, **EDA**, **preprocessing**, **modeling**, and **evaluation**  
- `loan-test.csv`: Dataset used for **training and evaluation**  

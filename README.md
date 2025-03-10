# Loan-Approval-Prediction-using-Machine-Learning

## 📌 Project Description 
This project focuses on predicting loan approvals using machine learning techniques. The dataset includes applicant details such as income, credit history, loan amount, employment status e.t.c The workflow involves data preprocessing, feature engineering. Various classification algorithms, including logistic regression,  K-Nearest Neighbors (KNN), Support Vector Machines (SVM) were implemented and compared. 

The best-performing model was selected based on evaluation metrics like accuracy, precision, recall, and F1-score. The project also explores feature scaling techniques and automated feature selection to enhance predictive accuracy.

## 📂 Dataset
The dataset contains 13 features : 
1. **Loan:**	A unique id
2. **Gender:**	Gender of the applicant Male/female
3. **Married:**	Marital Status of the applicant, values will be Yes/ No.
4. **Dependents:**	It tells whether the applicant has any dependents or not.
5. **Education:**	It will tell us whether the applicant is Graduated or not.
6. **Self_Employed:**	This defines that the applicant is self-employed i.e. Yes/ No.
7. **ApplicantIncome:**	Applicant income
8. **CoapplicantIncome:**	Co-applicant income
9. **LoanAmount:**	Loan amount (in thousands)
10. **Loan_Amount_Term:**	Terms of loan (in months)
11. **Credit_History:**	Credit history of individual’s repayment of their debts
12. **Property_Area:**	Area of property i.e. Rural/Urban/Semi-urban.
13. **Loan_Status:**	Status of Loan Approved or not i.e. Y- Yes, N-No.

## ⚙️ Installation and Requirement
1. Clone the repository.
```
bash git clone Loan-Approval-Prediction-using-Machine-Learning.git
```
2. Navigate to the project directory
```
cd Loan-Approval-Prediction-using-Machine-Learning

```
3. Install Dependencies
```
pip install -r requirements.txt
```

## 📊 Data Preprocessing & Feature Engineering
- Handled missing values using median/mode imputation.
- Encoded categorical variables using Label Encoding.
- Scaled numerical features using StandardScaler/MinMaxScaler.
- Automated feature selection techniques to improve model performance.

## 🔍 Exploratory Data Analysis (EDA)
- Visualized distributions of key features.
- Checked correlations using a heatmap.
- Analyzed feature importance for better insights.

## 🤖 Machine Learning Models
The following classification models were implemented:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## 📈 Model Performance
| Model	| Accuracy	| Precision	| Recall	| F1-Score |
| ------ | -------- | --------| ----------| --------- |
|K-Nearest Neighbors | 70.4% | 63% | 59% | 60% |
| Support Vector Machine | 65.4% | 47% | 49% | 45% |
| Random Forest | 82.5% | 80% | 77% | 78% |
| Logistic Regression	| 82.5% | 85% | 73% | 76% |

- Random Forest (RF) and Logistic Regression (LR) models are performing the best, both achieving 82.5% accuracy.
- However, Random Forest has a better balance between precision and recall, making it more robust for generalization.
- Worst performer was Support Vector Machine with 65.4% accuracy and the lowest F1-score (45%).


# LOAN-PREDICTION-USING-MACHINE-LEARNING
Loan approval is one of the most important decision-making processes in the banking and financial sector. Financial institutions receive thousands of loan applications, making manual evaluation time-consuming and prone to human error. This project develops a Machine Learning model that predicts whether a loan application will be approved or rejected based on an applicant's demographic, financial, and credit-related information.

The project follows a complete Machine Learning pipeline, starting from data preprocessing to model evaluation and comparison. Multiple classification algorithms are trained and evaluated to determine the most accurate model for loan approval prediction.
Predict loan approval status using Machine Learning.
Perform comprehensive data preprocessing and cleaning.
Handle missing values and categorical variables.
Scale numerical features for improved model performance.
Address class imbalance using SMOTE.
Compare multiple classification algorithms.
Evaluate models using various performance metrics.
Select the best-performing model for prediction.
📂 Dataset Features

The dataset includes applicant information such as:

Gender
Married Status
Dependents
Education
Self Employment Status
Applicant Income
Co-applicant Income
Loan Amount
Loan Amount Term
Credit History
Property Area

Target Variable

Loan Status (Approved / Rejected)
🧹 Data Preprocessing

The following preprocessing steps were performed:

Removed unnecessary columns (Loan_ID).
Checked dataset information and summary statistics.
Identified missing values.
Replaced missing values using:
Mode for categorical features
Median for numerical features with skewed distributions
Converted categorical variables into numerical format using Label Encoding.
Applied feature scaling using:
StandardScaler
MinMaxScaler (for comparison)
Split the dataset into Features (X) and Target (y).
Performed an 80:20 Train-Test Split using random_state=42.

To improve prediction performance on the minority class, the dataset was balanced using SMOTE (Synthetic Minority Over-sampling Technique) before training the models.

Benefits of SMOTE:

Reduces model bias toward the majority class.
Improves Recall and F1-Score.
Creates synthetic samples instead of duplicating existing ones.

The following classification algorithms were implemented:

1. Logistic Regression
Simple and interpretable baseline model.
Suitable for binary classification.
2. Decision Tree Classifier
Learns decision rules from data.
Easy to visualize and interpret.
3. Random Forest Classifier
Ensemble learning method combining multiple decision trees.
Reduces overfitting.
Provides better generalization and higher accuracy.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Jupyter Notebook

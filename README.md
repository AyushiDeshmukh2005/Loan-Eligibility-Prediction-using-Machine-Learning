# Loan-Eligibility-Prediction-using-Machine-Learning

Overview
A Machine Learning project that predicts whether a loan will be approved or rejected based on applicant details such as income, credit history, education and employment. It uses models like Logistic Regression, Naive Bayes and Decision Tree to classify loan status and evaluate performance using accuracy and confusion matrix. The goal is to build models that can accurately classify whether a loan will be approved or not.

Technologies Used
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Scikit-learn

Project Workflow
1. Data Loading
Dataset is loaded using Pandas
Initial exploration and inspection performed
2. Data Preprocessing
Handling missing values using imputation
Removing highly correlated features using correlation matrix
Feature selection based on correlation threshold
3. Data Visualization
Correlation heatmap plotted using Seaborn
4. Train-Test Split
Dataset split into training and testing sets (80:20)

Models Used
1. Logistic Regression
Used as a baseline model
2. Naive Bayes (GaussianNB)
Implemented using pipeline with missing value handling
3. Decision Tree Classifier
Built using entropy criterion
Also tested with limited depth for optimization

Evaluation Metrics
1.Accuracy Score
2.Confusion Matrix
These metrics help evaluate how well the models perform on unseen data.
<img width="655" height="504" alt="image" src="https://github.com/user-attachments/assets/56e593bb-3393-4079-9505-6862ef146d81" />

Results
1.Multiple models were trained and compared
2.Naive Bayes showed effective performance
3.Accuracy scores and confusion matrices were used for comparison
<img width="686" height="234" alt="image" src="https://github.com/user-attachments/assets/ce0afd7c-6269-45ae-880f-0340d4e2c346" />





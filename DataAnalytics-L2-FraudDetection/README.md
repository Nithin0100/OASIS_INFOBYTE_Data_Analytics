# Oasis Infobyte Internship — Task 03: Fraud Detection

## Objective
To identify potentially fraudulent credit card transactions using machine learning techniques. The project focuses on exploratory data analysis, class imbalance handling, model training, and evaluation using appropriate classification metrics.

## Dataset
- Dataset: Credit Card Fraud Detection dataset
- Original file: `credit_card_fraud_10k.csv`
- Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab

## Work Completed
- Loaded and inspected the transaction dataset.
- Checked missing values, duplicate records, and data types.
- Analyzed the distribution of fraudulent and legitimate transactions.
- Performed exploratory data analysis on transaction amounts and transaction hours.
- Examined fraud patterns across merchant categories.
- Analyzed foreign transactions and location mismatches.
- Created a correlation heatmap for numerical features.
- Identified class imbalance between fraudulent and legitimate transactions.
- Prepared input features and the target variable.
- Applied one-hot encoding to categorical features and scaling to numerical features.
- Split the dataset into training and testing sets using stratified sampling.
- Trained Logistic Regression, Decision Tree, and Random Forest classifiers.
- Used balanced class weights to help address class imbalance.
- Evaluated models using accuracy, precision, recall, F1-score, ROC-AUC, and Average Precision.
- Generated classification reports and confusion matrices.
- Compared model performance using charts and a comparison table.
- Visualized Random Forest feature importance.
- Exported model comparison and feature importance results to CSV files.

## Files
- `Oasis_Infobyte_L2_Task_03_Fraud_Detection.ipynb` — Jupyter notebook containing the code and analysis.
- `credit_card_fraud_10k.csv` — dataset containing credit card transaction records.
- `fraud_detection_model_comparison.csv` — comparison of classification model performance.
- `fraud_detection_feature_importance.csv` — feature importance scores from the Random Forest model.

## Conclusion
The project demonstrates how machine learning can be used to identify potentially fraudulent transactions. Multiple classification models are compared using suitable evaluation metrics, with particular attention to fraud detection recall, precision, and class imbalance. The results help identify a suitable model for the dataset while highlighting the need for further validation before real-world deployment.

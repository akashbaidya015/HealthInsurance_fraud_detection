Healthcare-Fraud-Detection
Business Problem
Identify potential fraudulent healthcare providers based on inpatient claims, outpatient claims and beneficiary details. This will help prevent huge losses incurred by health insurance companies or the government by identifying health care providers who make fraud claims on behalf of their beneficiaries and help them to disburse insurance money to beneficiaries who truly deserve it. This will also help in bringing down the premium costs for insurance and thereby making healthcare more affordable.

Machine Learning Problem
This is a binary classification problem. Using data of inpatient claims, outpatient claims and beneficiary details, we have to find the right indicator variables to predict whether a healthcare provider is fraud or not.

Business Constraints

The cost of misclassification can be very high.
The number of false negatives should be less.
No strict latency concerns.
Model interpretability is important. A probability of the provider being a fraud can be provided to make a more informed decision.

# Performance Metrics Used

Recall
Precision
F1 Score
AUC Score

# Datassets

The 4 Datasets used are 
combined_beneficiary.csv
combined_data.csv
combined_inpatient.csv
combined_outpatient.csv

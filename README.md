# Credit Risk Analysis Report and Credit Risk Classification 
Objective: This project aims to use various techniques to train and evaluate a model based on loan risk. We will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. We also assess the accuracy, precision, and recall of the model to determine its suitability for use by the company.

# Model Performance Metrics
Accuracy: The model achieved an impressive accuracy of 0.99, indicating strong overall predictive performance.
Precision (Class 1 - High-Risk Loans): The precision for high-risk loans (Class 1) is 0.88. This means that when the model predicts a loan as high-risk, it is correct 88% of the time.
Recall (Class 1 - High-Risk Loans): The recall (sensitivity) for high-risk loans is 0.91. This indicates that the model correctly identifies 91% of actual high-risk loans.
F1-Score (Class 1 - High-Risk Loans): The F1-score, which balances precision and recall, is 0.89. It reflects a good trade-off between precision and recall.

## Summary and Recommendation
The logistic regression model demonstrates robust performance across both healthy (Class 0) and high-risk (Class 1) loans. Here are the key takeaways:

Healthy Loans (Class 0):
Precision, recall, and F1-score are all excellent (close to 1.00).
The model accurately predicts healthy loans, with strong support (15011 instances).
High-Risk Loans (Class 1):
Precision is good (0.88), indicating reliable identification of high-risk loans.
Recall is high (0.91), capturing most actual high-risk loans.
The F1-score balances precision and recall effectively (0.89).
Recommendation: Based on the model’s performance, I recommend using it for credit risk assessment. However, continuous monitoring and periodic model evaluation are essential to ensure its reliability over time.

## Acknowledgments
Leveraged Google, ChatGPT, and Copilot as/where needed to develop/validate/troubleshoot code/data/functions. The Python and data science community for their invaluable resources.

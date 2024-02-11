# Credit Risk Analysis Report | Module 12
## By: Dina Uddin


### Overview:
The purpose of this analysis is to assess the performance of logistic regression models in credit risk prediction. The study focuses on handling imbalanced datasets and explores the impact on model performance. Specifically, the analysis aims to provide insights into the trade-offs and advantages of using logistic regression on imbalanced credit datasets, with a focus on oversampling techniques.

### Model Performance Metrics:

Original Data:

- Balanced Accuracy Score: 0.9520
- Precision (Label 0 - Healthy Loan): 1.00
- Recall (Label 0 - Healthy Loan): 0.99
- Precision (Label 1 - High-Risk Loan): 0.85
- Recall (Label 1 - High-Risk Loan): 0.91

Resampled Data:
- Balanced Accuracy Score: 0.9937
- Precision (Label 0 - Healthy Loan): 1.00
- Recall (Label 0 - Healthy Loan): 0.99
- Precision (Label 1 - High-Risk Loan): 0.84
- Recall (Label 1 - High-Risk Loan): 0.99

### Summary:
The logistic regression model on the original data demonstrates commendable performance, with high accuracy and reasonable precision and recall for both healthy and high-risk loans. However, the model fitted with oversampled data exhibits superior performance, achieving near-perfect accuracy and improved precision and recall scores, especially for high-risk loans.

### Recommendation:
Based on the comparison, the logistic regression model on the resampled data is recommended for credit risk prediction. The oversampling technique significantly enhances the model's ability to identify high-risk loans without compromising its performance on healthy loans. This recommendation aligns with the goal of minimizing the risks associated with credit prediction in the financial sector.

### Justification:
The oversampled model outperforms the original model in all aspects, demonstrating superior sensitivity to high-risk loans. This is crucial for financial institutions where identifying potential credit defaults is of utmost importance. The increased recall for high-risk loans in the oversampled model makes it a more robust choice for practical applications in credit risk prediction.
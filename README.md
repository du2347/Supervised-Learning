# Supervised Learning in Credit Risk Prediction: Evaluating Logistic Regression Models with Imbalanced Datasets in Fintech

## Executive Summary:
This research project, centered around supervised learning, aims to assess the effectiveness of logistic regression models in predicting credit risk within the fintech domain. Utilizing a labeled dataset of historical lending activity from a peer-to-peer lending services company, the study explores the application of supervised learning techniques to train and evaluate logistic regression models on both the original and resampled datasets. The goal is to analyze the performance metrics and provide insights into the practical implications of employing logistic regression for credit risk assessment in a supervised learning framework.

## Objectives:
1. Evaluate the supervised learning performance of logistic regression models on the original imbalanced dataset.
2. Implement RandomOverSampler from imbalanced-learn to resample the data, addressing challenges posed by imbalanced classes in supervised learning.
3. Compare accuracy scores, confusion matrices, and classification reports of logistic regression models on both the original and resampled datasets in the context of supervised learning.
4. Provide recommendations for the practical application of logistic regression in credit risk prediction within a supervised learning paradigm.

## Methodology:
- Data Preprocessing:
    - Read lending_data.csv into a Pandas DataFrame.
    - Created labels (y) from the "loan_status" column and features (X) from the remaining columns.
    - Checked the balance of labels using the value_counts function.
    - Split the data into training and testing datasets using train_test_split.
- Logistic Regression on Original Data:
    - Fit a logistic regression model using X_train and y_train.
    - Saved predictions for the testing data labels (X_test).
    - Evaluated the model's performance: accuracy score, confusion matrix, and classification report.
- Logistic Regression on Resampled Data:
  - Used RandomOverSampler to balance the dataset.
  - Fit a logistic regression model using the resampled data.
  - Saved predictions for the testing data labels.
  - Evaluated the model's performance: accuracy score, confusion matrix, and classification report.
- Credit Risk Analysis Report:
  - Provided an overview explaining the purpose of the analysis.
  - Using bulleted lists, describe both models' balanced accuracy, precision, and recall scores.
  - Summarized results, comparing predictions on the original and resampled datasets.
  - Offered recommendations for the model's practical use in credit risk prediction.

## Final Remarks & Global Implications

This research project contributes insights into the performance of logistic regression models in credit risk prediction and addresses the challenges posed by imbalanced datasets. The findings provide valuable guidance for financial practitioners, shedding light on the trade-offs and advantages associated with using logistic regression on imbalanced credit datasets. Moreover, incorporating supervised learning techniques plays a pivotal role in enhancing the predictive capabilities of the models, making the analysis more robust and applicable in real-world fintech scenarios.

The global implications of this research extend beyond the application of logistic regression models in credit risk prediction. This is a critical aspect of the financial sector, where the significance of supervised learning techniques comes to the forefront. Understanding how imbalanced data impacts model performance, especially in a supervised learning framework, can significantly enhance decision-making processes for financial institutions worldwide. The findings influence the global adoption of effective strategies, such as oversampling techniques, to mitigate credit risk, emphasizing the role of supervised learning in addressing challenges posed by imbalanced datasets. The study's insights contribute to the broader global discourse on handling imbalanced datasets, making the findings relevant and applicable across diverse financial markets.

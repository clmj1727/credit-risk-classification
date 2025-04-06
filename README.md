# Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis is to build a machine learning model that predicts the credit risk of borrowers using historical lending data from a peer-to-peer lending platform. By identifying patterns in the features associated with past loans, the goal is to classify future loans as either **healthy (0)** or **high-risk (1)**. This predictive capability can help lenders reduce default rates and improve loan approval strategies.

To achieve this, a **logistic regression model** was trained on preprocessed data. The model’s performance was evaluated using accuracy, precision, recall, and F1-score—key metrics that measure how well the model identifies both healthy and high-risk loans.

---

## Results

The following performance metrics were obtained from the classification report:

- **Accuracy**: 99%  
- **Precision**:
  - Class 0 (Healthy Loans): 1.00
  - Class 1 (High-Risk Loans): 0.84
- **Recall**:
  - Class 0 (Healthy Loans): 0.99
  - Class 1 (High-Risk Loans): 0.94
- **F1-Score**:
  - Class 0: 1.00
  - Class 1: 0.89

---

## Summary and Recommendation

The logistic regression model demonstrates **exceptional performance** in identifying both healthy and high-risk loans. With an overall accuracy of **99%**, the model correctly classifies the vast majority of loan outcomes. Most importantly, it achieves a **94% recall** on high-risk loans, which indicates a strong ability to detect potential defaults—critical for minimizing financial losses.

Although the **precision for high-risk loans is slightly lower (84%)**, this is acceptable in a credit risk context where **missing a high-risk borrower (false negative)** is typically more costly than occasionally flagging a healthy one (false positive).

### Recommendation:

Based on its high accuracy and strong recall for high-risk loans, this logistic regression model is **recommended for deployment**. It provides a reliable foundation for credit risk assessment, supporting better decision-making for the lending institution.

---
# Acknowledgements:
Special thanks to Dr. Carl Arrington for guidance during the Supervised Machine Learning and Classification Models implementation. Some snippets and logic were developed following in-class tutorial support and discussions.

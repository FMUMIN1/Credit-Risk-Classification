# Credit-Risk-Classification
Supervised Machine Learning Model:

 * Utilizing machine learning techniques, an in-depth analysis is conducted on a dataset comprising historical lending activity from a peer-to-peer lending services company. The primary objective is to construct a robust model capable of accurately assessing the creditworthiness of borrowers. By leveraging advanced algorithms and statistical methods, this approach enables the identification of reliable indicators and patterns, facilitating informed lending decisions and mitigating potential risks.

# ANALYSIS


# RESULTS

* Logistic Regression Model 1:
  * 0.9508986295555389: ![classification_report_1](https://github.com/FMUMIN1/Credit-Risk-Classification/assets/121820268/bd939872-094e-4232-ba33-7844d7d3c823)

* Logistic Regression Model 2:
  * 0.9944768245409253: ![classification_report_2](https://github.com/FMUMIN1/Credit-Risk-Classification/assets/121820268/438b0ac7-e017-4d03-8772-ee0b00b749d6)
 

# SUMMARY
The collected data proves effective for training and testing the Machine Learning Classification Model. To enhance predictions, addressing the issue of imbalanced sampling is crucial. Implementing random oversampling significantly improves balanced accuracy and recall scores. By achieving a higher recall value, the model becomes more adept at accurately identifying risky loans.

However, incorrect predictions pose two challenges. False positives occur when users are mistakenly flagged as risky despite being creditworthy, while false negatives arise when risky users go unnoticed. Both cases carry associated costs. Hence, it is imperative for the model to excel in accuracy for both 1s (risky loans) and 0s (healthy loans), ensuring comprehensive and reliable predictions.

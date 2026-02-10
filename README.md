**Comparative Analysis of Machine Learning Classification Models Using Performance Evaluation Metrics**


a) **Problem Statement** This Assignment aims to implement and evaluate six widely used machine learning classification models on a single dataset to ensure fair and consistent comparison. The models include Logistic Regression, Decision Tree, K-Nearest Neighbors, Naive Bayes, Random Forest, and XGBoost. Each model’s performance will be assessed using Accuracy, AUC Score, Precision, Recall, F1 Score, and Matthews Correlation Coefficient (MCC). The objective is to identify the most effective classification approach based on comprehensive metric-based evaluation.

b) **Data set Overview** This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005..

**Data set Description**: - The Default of Credit Card Clients Dataset contains financial and demographic information of credit card holders in Taiwan from April to September 2005. It includes client demographics, credit limits, repayment history, bill statement amounts, and past payment details. The dataset consists of 25 variables, each representing monthly financial behavior and personal attributes of individual clients. The target variable indicates whether a client defaulted on their credit card payment in the following month. This dataset is widely used for credit risk analysis and default prediction modeling.

**c) Table with the evaluation metrics calculated for all the 6 models as below**

| Model                     | Accuracy | AUC    | Precision | Recall | F1 Score | MCC    |
|---------------------------|----------|--------|-----------|--------|----------|--------|
| Logistic Regression       | 0.5798   | 0.7344 | 0.3106    | 0.7378 | 0.4372   | 0.2267 |
| Decision Tree             | 0.7357   | 0.6116 | 0.3997    | 0.3888 | 0.3942   | 0.2252 |
| kNN                       | 0.8120   | 0.7527 | 0.6164    | 0.3971 | 0.4830   | 0.3882 |
| Naive Bayes               | 0.7155   | 0.7525 | 0.4127    | 0.6767 | 0.5127   | 0.3481 |
| Random Forest (Ensemble)  | 0.8153   | 0.7804 | 0.6026    | 0.4846 | 0.5372   | 0.4275 |
| XGBoost (Ensemble)        | 0.8277   | 0.7911 | 0.6798    | 0.4175 | 0.5173   | 0.4381 |


**d. Observations on the performance of each model**
Logistic Regression:
The Logistic Regression model achieves an accuracy of 0.58, which is the lowest among all models. It shows a high recall of 0.74, indicating that most positive instances are correctly identified. However, the precision is very low (0.31), resulting in a high number of false positives. The F1-score of 0.44 reflects poor balance between precision and recall. The low MCC (0.23) suggests weak overall classification quality and limited reliability.
________________________________________
Decision Tree:
The Decision Tree model records an accuracy of 0.74, showing moderate predictive performance. Its AUC value of 0.61 is the lowest, indicating poor ability to distinguish between classes. Precision (0.40) and recall (0.39) are nearly equal, suggesting balanced but weak predictions. The F1-score (0.39) confirms limited effectiveness. The MCC of 0.23 indicates minimal improvement over random classification.
________________________________________
k-Nearest Neighbors (kNN):
The kNN model achieves a high accuracy of 0.81, indicating strong overall performance. It also records a good AUC of 0.75, showing effective class separation. Precision is relatively high (0.62), meaning predicted positives are often correct. However, recall is low (0.40), indicating many positive cases are missed. The F1-score (0.48) and MCC (0.39) suggest moderate classification balance.
________________________________________
Naive Bayes:
Naive Bayes attains an accuracy of 0.72, indicating stable performance. It shows a high recall of 0.68, effectively identifying positive instances. Precision (0.41) is moderate, leading to some false positives. The F1-score of 0.51 reflects better balance compared to Logistic Regression and Decision Tree. The MCC (0.35) indicates reasonable overall predictive reliability.
________________________________________
Random Forest (Ensemble):
The Random Forest model achieves a high accuracy of 0.82, demonstrating strong predictive capability. Its AUC of 0.78 indicates good class discrimination. Precision (0.60) and recall (0.48) show balanced ensemble performance. The F1-score (0.54) is among the highest, reflecting effective learning. A higher MCC (0.43) confirms improved robustness and reliability.
________________________________________
XGBoost (Ensemble):
XGBoost records the highest accuracy of 0.83, making it the best-performing model. It also achieves the highest AUC (0.79), indicating excellent class separation. Precision is high (0.68), reducing false positives significantly. Although recall (0.42) is moderate, overall balance is strong. The highest MCC (0.44) confirms superior and consistent predictive performance.


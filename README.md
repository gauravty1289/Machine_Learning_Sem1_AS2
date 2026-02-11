**Comparative Analysis of Machine Learning Classification Models Using Performance Evaluation Metrics**



a) **Problem Statement** This Assignment aims to implement and evaluate six widely used machine learning classification models on a single dataset to ensure fair and consistent comparison. The models include Logistic Regression, Decision Tree, K-Nearest Neighbors, Naive Bayes, Random Forest, and XGBoost. Each model’s performance will be assessed using Accuracy, AUC Score, Precision, Recall, F1 Score, and Matthews Correlation Coefficient (MCC). The objective is to identify the most effective classification approach based on comprehensive metric-based evaluation.

b) **Dataset Overview** This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005..

**Dataset Description**: - The Default of Credit Card Clients Dataset contains financial and demographic information of credit card holders in Taiwan from April to September 2005. It includes client demographics, credit limits, repayment history, bill statement amounts, and past payment details. The dataset consists of 25 variables, each representing monthly financial behavior and personal attributes of individual clients. The target variable indicates whether a client defaulted on their credit card payment in the following month. This dataset is widely used for credit risk analysis and default prediction modeling.

**c) Table with the evaluation metrics calculated for all the 6 models as below**

|Model|Accuracy|AUC|Precision|Recall|F1 Score|MCC|
|-|-|-|-|-|-|-|
|Logistic Regression|0.5798|0.7344|0.3106|0.7378|0.4372|0.2267|
|Decision Tree|0.7357|0.6116|0.3997|0.3888|0.3942|0.2252|
|kNN|0.8120|0.7527|0.6164|0.3971|0.4830|0.3882|
|Naive Bayes|0.7155|0.7525|0.4127|0.6767|0.5127|0.3481|
|Random Forest (Ensemble)|0.8153|0.7804|0.6026|0.4846|0.5372|0.4275|
|XGBoost (Ensemble)|0.8277|0.7911|0.6798|0.4175|0.5173|0.4381|



**d. Observations on the performance of each model**



**| ML Model Name | Observation about Model Performance |**

**|---------------|--------------------------------------|**

**| Logistic Regression | Logistic Regression achieved the lowest accuracy (0.5798) among all models. It shows a very high recall (0.7378), meaning it detects most positive cases. However, the precision is very low (0.3106), leading to many false positives. The low MCC (0.2267) indicates weak overall predictive reliability. |**

**| Decision Tree | Decision Tree achieved moderate accuracy (0.7357) but relatively low AUC (0.6116). Precision and recall are both low and nearly balanced, resulting in a modest F1-score (0.3942). The MCC (0.2252) suggests limited predictive strength. Overall, it performs better than Logistic Regression in accuracy but lacks strong class discrimination. |**

**| kNN | kNN delivers strong accuracy (0.8120) and a solid AUC (0.7527). It has good precision (0.6164) but lower recall (0.3971), meaning it misses several positive instances. The F1-score (0.4830) shows moderate balance. Its MCC (0.3882) reflects improved overall reliability compared to simpler models. |**

**| Naive Bayes | Naive Bayes achieves reasonable accuracy (0.7155) with a good AUC (0.7525). It maintains strong recall (0.6767), detecting many positive cases. The F1-score (0.5127) indicates better balance than Decision Tree and Logistic Regression. The MCC (0.3481) shows moderate predictive capability. |**

**| Random Forest (Ensemble) | Random Forest provides high accuracy (0.8153) and strong AUC (0.7804). It balances precision (0.6026) and recall (0.4846) effectively. The F1-score (0.5372) indicates consistent performance. A higher MCC (0.4275) confirms its strong overall classification reliability. |**

**| XGBoost (Ensemble) | XGBoost achieves the highest accuracy (0.8277) and best AUC (0.7911). It also delivers the highest precision (0.6798), reducing false positives. Although recall is moderate (0.4175), the model maintains strong overall performance. The highest MCC (0.4381) makes it the best-performing model overall. |**




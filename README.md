The Telco Customer Churn dataset contains information about a telecommunications company's customers and their subscription details. The main goal of this dataset is to predict customer churn, that is, the customers who leave the company and stopped using their services. Understanding the factors that contribute to customers leaving can help the company develop strategies to retain customers.
The Exploratory Data Analysis (EDA) and prediction modeling (decision tree) for churn prediction have provided several key insights.

Firstly, it was observed that customers with shorter tenures tend to have higher churn rates, showing potential issues with early customer satisfaction or onboarding processes.

Additionally, higher monthly charges are correlated with higher churn, suggesting that cost-sensitive customers may perceive the service as too expensive.

Subscription to additional services such as Online Security, Tech Support, and Streaming Services is associated with lower churn rates, indicating that customers who engaged with more services are more likely to remain loyal.

Contract type also plays a crucial role, with month-to-month contracts showing higher churn rates compared to one or two-year contracts, which provide more stability and incentives for customers to stay.
Payment methods further influence churn, with customers using electronic check payments showing higher churn rates compared to those using credit cards or bank transfers, potentially reflecting differences in customer demographics or preferences.
For model perfomance, the Decision Tree model achieved an accuracy of 78%, with a higher precision (82%) and recall (91%) for predicting non-churners (class 0).

However, the model's performance is less robust for predicting churners (class 1), with precision at 63% and recall at 44%.
This imbalance shows that while the model is good at identifying customers who will stay, it is less effective at correctly identifying those who will leave.
Additionally, features such as tenure and total charges emerged as the most important predictors of churn, aligning with the EDA findings.

The Decision Tree model achieved an overall accuracy of 78%, performing better at predicting non-churners than churners, indicating a need for improvement in identifying potential churners.
This performance discrepancy highlights the necessity for additional data or model refinement.
Overall, both intrinsic customer behaviors (like tenure and service usage) and external factors (like contract type and payment method) significantly influence churn.
Addressing these areas through targeted strategies can enhance customer retention and reduce churn rates.


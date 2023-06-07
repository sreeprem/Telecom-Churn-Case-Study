# Telecom-Churn-Case-Study
Telecom-Churn-Case-Study

## Problem Statement
### Business Problem Overview

The problem at hand is focused on the telecom industry, where customers have the freedom to choose from various service providers and frequently switch between them. This industry faces a significant annual churn rate, with customers leaving their current operator for another. As the cost of acquiring new customers far exceeds the cost of retaining existing ones, telecom companies are now placing greater importance on retaining profitable customers.

The objective of this project is to predict which customers are likely to churn in order to reduce customer attrition. By analyzing customer-level data from a prominent telecom company, we aim to develop predictive models that can identify customers at a high risk of churning. Additionally, we will determine the key factors that contribute to customer churn.



In the telecom industry, there are two primary payment models: postpaid and prepaid. In the postpaid model, customers receive a monthly or annual bill based on their usage of the services. When these customers decide to switch to another telecom operator, they typically inform their current operator, making it clear that they have churned.

On the other hand, in the prepaid model, customers pay or recharge their accounts with a certain amount in advance and then utilize the services. When prepaid customers wish to switch to a different network, they can simply stop using the services without any prior notice. This makes it challenging to determine whether a customer has genuinely churned or is temporarily not using the services (e.g., due to traveling abroad and planning to resume usage later).

As a result, predicting churn becomes more critical and complex for prepaid customers, requiring careful definition of the term "churn." It's worth noting that the prepaid model is more prevalent in India and Southeast Asia, while the postpaid model is more common in Europe and North America.

For this project, the focus will be on the Indian and Southeast Asian markets, where the prepaid model is dominant.

### Churn 
In the context of this project, we will adopt the usage-based definition of churn. This definition considers customers who have not utilized any services, such as making outgoing calls, using mobile internet, or sending SMS messages, over a specific period of time.

By focusing on usage patterns, we aim to identify customers who have stopped actively engaging with the telecom services. However, it is important to note that this definition has a potential shortcoming. In situations where a customer has temporarily ceased using the services but intends to resume in the future, predicting churn based on a specific duration of zero usage may not be effective. For example, if we define churn as "two months of zero usage," it may be too late to take corrective actions to retain the customer since they may have already switched to another operator.

Nevertheless, for the purposes of this project, we will utilize the usage-based definition of churn as it provides a practical starting point for identifying customers at risk of attrition.

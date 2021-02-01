# Telecom-Churn-Case-Study

_Business Objective_

To analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

_Definition of Churn_

In ths project , we will use the usage-based definition to define churn i.e ustomers who have not done any usage, either incoming or outgoing - in terms of calls, internet etc. over a period of time.

_Understanding Customer Behaviour During Churn_

Customers usually do not decide to switch to another competitor instantly, but rather over a period of time (this is especially applicable to high-value customers). In churn prediction, we assume that there are three phases of customer lifecycle :

* The ‘good’ phase: In this phase, the customer is happy with the service and behaves as usual.

* The ‘action’ phase: The customer experience starts to sore in this phase, for e.g. he/she gets a compelling offer from a  competitor, faces unjust charges, becomes unhappy with service quality etc. In this phase, the customer usually shows different behaviour than the ‘good’ months. Also, it is crucial to identify high-churn-risk customers in this phase, since some corrective actions can be taken at this point (such as matching the competitor’s offer/improving the service quality etc.)

* The ‘churn’ phase: In this phase, the customer is said to have churned. You define churn based on this phase. Also, it is important to note that at the time of prediction (i.e. the action months), this data is not available to you for prediction. 

_Data Preparation_

1. Derived New Features 
2. Filter high-value customers
3.Tag churners and remove attributes of the churn phase

_ALGORITHM_

Intially, the  number of variables were reduced using PCA . and Used several Machine Learning Algorithms such as Logistic regression, Decision Trees, Random Forest, Gradient
Boosting.

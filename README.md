# MachineLearningprojectphase3

C:\Users\USER\Documents\MachineLearningprojectphase3\telecoms image.jpg


Overview:


Telecom companies face revenue losses from customer churn. Understanding churn factors is crucial for profitability. This project analyzes customer data to identify churn patterns, develop predictive models, and segment customers. The goal is to enhance service quality, customer satisfaction, and operational efficiency, aiding strategic decisions to boost performance and loyalty.


Business Understanding
In this project, the primary objective is to predict customer churn for a telecommunications company. Customer churn refers to the scenario when customers stop using a company's services. By accurately predicting churn, the company can take proactive measures to retain customers, thereby reducing revenue loss and improving customer satisfaction.


The key stakeholders for this project include:

Marketing Team: Interested in identifying at-risk customers and designing targeted retention campaigns.
Customer Service Team: Wants to understand the reasons behind churn and improve service quality.
Product Development Team: Can use insights to enhance product features and offerings.
Senior Management: Needs to make strategic decisions based on churn predictions to maximize profitability and growth.


Data Used
The data set ws obtained from Syril Telecommunication company.
The dataset used for this project is Churmdata.csv, which contains the following features:

State: The US state in which the customer resides.
Account Length: Duration of the account in days.
Area Code: The area code of the customer’s phone number.
International Plan: Whether the customer has an international plan (yes/no).
Voice Mail Plan: Whether the customer has a voice mail plan (yes/no).
Number of VMail Messages: Number of voice mail messages.
Total Day Minutes: Total minutes of calls during the day.
Total Day Calls: Total number of calls during the day.
Total Day Charge: Total charge for calls during the day.
Total Eve Minutes: Total minutes of calls during the evening.
Total Eve Calls: Total number of calls during the evening.
Total Eve Charge: Total charge for calls during the evening.
Total Night Minutes: Total minutes of calls during the night.
Total Night Calls: Total number of calls during the night.
Total Night Charge: Total charge for calls during the night.
Total Intl Minutes: Total minutes of international calls.
Total Intl Calls: Total number of international calls.
Total Intl Charge: Total charge for international calls.
Customer Service Calls: Number of calls to customer service.
Churn: Whether the customer churned (yes/no).



Modeling Used
The following machine learning models were used to predict customer churn:

Logistic Regression: A baseline model to establish a benchmark for other models.
Decision Trees: Used for their interpretability and ability to capture non-linear relationships.
Random Forest: An ensemble method that improves the performance and accuracy over single decision trees.
KNN model:The KNN model was also used, providing additional insights into customer behavior and further validating the model's effectiveness


Model Evaluation
Models were evaluated based on the following metrics:

Accuracy: The proportion of correctly classified instances.
Precision: The proportion of true positive predictions among all positive predictions.
Recall: The proportion of true positive predictions among all actual positives.
F1 Score: The harmonic mean of precision and recall, providing a balance between the two.
ROC curve comparison.

Recommedations.

Conduct Detailed Analyses:

Perform in-depth analyses, including surveys and feedback, to identify primary churn factors, particularly in Area Code 415.
Reevaluate Voicemail Plan:

Consider repositioning the voicemail plan as an optional add-on rather than a standard feature.
Implement Loyalty Programs:

Introduce loyalty programs to reward long-term customers, especially those with accounts longer than 80 days, to incentivize retention.
Promote Evening and Night Plans:

Develop and promote bundled evening and night plans, offering incentives for high users (above the 75th percentile) to upgrade.
Optimize Call Charges:

Regularly review and adjust day, evening, night, and international charges to stay competitive, focusing on evening charges for targeted revenue optimization.
Leverage Predictive Models:

Use the Random Forest model, identified as the best performer, to predict customer churn and implement proactive retention strategies.
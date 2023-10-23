## **SyriaTel Customer Churn Prediction**
Author: Frank Mandele
![Alt text](image-1.png)


## **Business Problem Statement**

SyriaTel, a telecommunications company, is determined to minimize customer churn and retain its valued customers. This project aims to leverage machine learning classification models to predict which customers are likely to discontinue their services with the company. By doing so, we can provide insights that will empower SyriaTel to make informed business decisions and take proactive steps to retain at-risk customers.

This project will be addressing the question, **"What business operations can the company do differently to improve upon their customer rentention?"**

## Data Overview
SyriaTel has provided a dataset that includes information about its customers. The dataset contains various features such as customer demographics, usage patterns, and historical interactions with the company. It also includes a binary target variable that indicates whether a customer has churned (True, 1) or not (False, 0).

## Project Objective
The primary objective of this project is to develop a predictive model that can accurately classify customers as likely to churn or not. By achieving this objective, SyriaTel can take targeted actions to retain at-risk customers, implement customer loyalty programs, or make adjustments to its services.

## Data Preparation

In this section, I handled missing data issues, dropped columns account length and state since I did not intend to use them in my analysis. I then proceeded to check for any duplicates in the data, encoded binary categorical features i.e. international plan and voice mail plan into binary values(1s and 0s) to aid in my analysis.
Finally I was able to scale my features with minmaxscaler to maintain the ranges of the values in my dataset to prepare for modeling.

## Modeling
There is employment of various machine learning classification models, including logistic regression, decision trees, and random forests. Logistic regression model formed the baseline model for this project before improving the models and introducing other models. These models were then trained and evaluated to determine which one provides the best predictive performance. 


## Evaluation
Model performance was then assessed using appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score. Followed by a confusion matrix to visualize model performance and make informed decisions about model selection.

Random forest metrics were used for this project as it provided the better results of the three models with an accuracy score of 93%

## Conclusion
Through our analysis and modeling efforts, we have identified several important insights regarding customer churn at SyriaTel:

* Approximately 14% of customers in the dataset have churned, highlighting the importance of addressing this issue.
* Almost half (42%) of the customers with international plan subscription churn
* Customers that stop doing business with the company spend relatively more than active customers
* Once a customer hit the 4th call to customer service, the chances of them churning increase significantly.

## Recommendations
To mitigate customer churn and improve customer retention, we recommend the following actions:

**Personalized Retention Strategies**: Implement personalized retention strategies based on the identified customer segments. Tailoring offers and services to the specific needs and preferences of each segment can significantly reduce churn rates.

**Proactive Customer Engagement**: Establish proactive customer engagement initiatives, including timely communication with at-risk customers, targeted promotions, and loyalty programs to enhance the customer experience.

**Feedback Mechanism**: Develop a feedback mechanism to gather insights from customers about their experiences and areas for improvement. Using customer feedback to make data-driven improvements can increase customer satisfaction and loyalty.


# SyriaTel Customer Churn Rate Analysis

![Image](https://github.com/kaluma-67/SyriaTel_Customer_Churn_Rate_Analysis/blob/master/Images/Churn_Analysis_Image.png)

## Project Overview
This project aims to analyse and predict the customer churn rate in SyriaTel, to assist the Customer Service and Sales & Marketing Teams in devicing techniques to reduce churn.

## Objectives
1. Analyze customer churn data to identify key factors contributing to customer churn.
2. Build a predictive model to forecast customer churn.
3. Provide actionable insights and recommendations to the Customer Service and Sales & Marketing teams.

## Key Questions
1. What is the overall churn rate?
2. What are the most significant factors contributing to customer churn?
3. How can the identified factors be addressed to reduce churn?
4. Which ML model would be most suitable to predict churn?

## Methodology
1. **Data Collection and Cleaning**:
   - Data was sourced from Kaggle.
   - Cleaned and preprocessed the data to ensure quality and consistency.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of features and their correlation with customer churn.
   - Identified key features impacting churn using statistical methods and visualizations.

3. **Model Building and Evaluation**:
   - Built and evaluated multiple models including Decision Trees, Random Forests, and XGBoost.
   - Selected XGBoost as the best-performing model with an accuracy of 93.3%.

## Key Findings
1. **Overall Churn Rate**:
   - The customer churn rate is 14.49%.

2. **Significant Factors Affecting Churn**:
   - Customers with a voice mail plan are less likely to churn.
   - Customers with an international plan have a higher churn rate.
   - Multiple customer service calls correlate with higher churn rates.
3. The XGBoost model has proven to be the most effective for predicting customer churn, with an accuracy of 93.3%

## Recommendations
### To The Customer Service Team
1. **Improve on complaint resolution**:
   Focus on improving the quality of customer service interactions, especially for customers making multiple calls. This could involve training the customer service personnel and creating effective customer service SOPs(Standard Operiting Procedures). Consider proactive outreach to customers who have called multiple times to ensure their issues have been resolved satisfactorily.

2. **Monitor and address frequent callers**:
  Identify customers who frequently contact customer service and monitor their interactions closely. Follow-up to ensure their issues are fully resolved.

3. **Implement a customer feedback system**:
  Implement a feedback system to gather customer opinions after intering with the customer service team. Use this data to continually improve the quality of service.

### To The Sales & Marketing Team
1. **Review the International plan**:
Reevaluate the international plan. Conduct surveys to understand the specific pain points customers are experiencing with this plan.This should be based on how the Voice mail plan is rolled out since customers with the later tend not to churn.
Market both plans more to ensure a higher adoption rate.
Offer a revised plan or additional benefits to address common issues and enhance customer satisfaction.

2. **Targeted Marketing Campaigns**:
Develop targeted campaigns for customers with international plans and frequent customer care callers to address their specific needs and reduce churn.
Highlight improvements and new features in marketing materials to reassure existing customers of the value they are receiving.

3. **Promotional offers and customer sensitization:**
Provide special promotions or discounts to customers identified as highly likely to churn. This can include loyalty programs or incentives for long-term commitment.
Create educational content to help customers better understand and utilize their plans. This can include tutorials and/or webinars.



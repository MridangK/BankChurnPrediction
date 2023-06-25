# Bank Churn Prediction

Bank churn prediction refers to the process of analyzing and predicting the likelihood of customers leaving a bank or terminating their relationship with it. It is a crucial task for banks and financial institutions, as customer churn can have significant negative impacts on their profitability and customer base. By employing various data analysis techniques and predictive models, bank churn prediction aims to identify patterns, trends, and factors that contribute to customer attrition. This enables banks to proactively take preventive measures, such as targeted retention strategies or personalized offers, to retain valuable customers and maintain a stable customer base. The ultimate goal of bank churn prediction is to optimize customer retention efforts, enhance customer satisfaction, and improve overall business performance.

## Dataset Exploration

The dataset used for bank churn prediction contains the following features:

1. **CLIENTNUM**: Unique identifier for each customer.
2. **Attrition_Flag**: Indicates whether the customer has churned (left) or not.
3. **Customer_Age**: Age of the customer.
4. **Gender**: Gender of the customer.
5. **Dependent_count**: Number of dependents the customer has.
6. **Education_Level**: Educational background of the customer.
7. **Marital_Status**: Marital status of the customer.
8. **Income_Category**: Income category of the customer.
9. **Card_Category**: Type of credit card the customer holds.
10. **Months_on_book**: Number of months the customer has been a customer of the bank.
11. **Total_Relationship_Count**: Total number of products the customer has with the bank.
12. **Months_Inactive_12_mon**: Number of months the customer has been inactive in the last 12 months.
13. **Contacts_Count_12_mon**: Number of times the customer has been contacted in the last 12 months.
14. **Credit_Limit**: Credit limit of the customer.
15. **Total_Revolving_Bal**: Total revolving balance (outstanding debt) of the customer.
16. **Avg_Open_To_Buy**: Average open to buy (credit available) of the customer.
17. **Total_Amt_Chng_Q4_Q1**: Ratio of total transaction amount change between Q4 and Q1.
18. **Total_Trans_Amt**: Total transaction amount in the last 12 months.
19. **Total_Trans_Ct**: Total transaction count in the last 12 months.
20. **Total_Ct_Chng_Q4_Q1**: Ratio of total transaction count change between Q4 and Q1.
21. **Avg_Utilization_Ratio**: Average utilization ratio of the customer's credit limit.

These features provide valuable insights into the characteristics and behaviors of customers that may contribute to churn. Analyzing these features and building predictive models can help in understanding the factors that influence customer attrition and enable banks to take proactive measures for customer retention.

Exploratory Data Analysis

During the exploratory data analysis, we examined the distribution of the age column using box plots and bar histograms. The analysis revealed the presence of two outliers in the age data. However, considering the small number of outliers and the fact that the age distribution follows a relatively normal pattern, it is reasonable to proceed with the dataset without removing these outliers.

The age feature exhibits a normal distribution, which aligns with our assumption of normality. This finding indicates that the age variable can be utilized as a reliable predictor in our analysis and modeling tasks.

By confirming the normality assumption for the age feature, we can proceed with further analysis and modeling with confidence in the integrity of this particular attribute.

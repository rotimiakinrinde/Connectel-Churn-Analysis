# Connectel-Churn-Analysis

### Business Introduction

Connectel is a leading telecommunications provider specialising in delivering reliable, high-quality connectivity solutions for individuals and businesses. With a focus on customer satisfaction, Connectel offers a range of services including mobile plans, broadband internet, and tailored communication solutions. The company strives to provide seamless connectivity, innovative technology, and exceptional customer service to meet the evolving needs of modern consumers.


### Problem Statement

This case study examines the impact of payment methods and technical support on customer churn. By analyzing these factors, we aim to provide insights that will help Connectel:

-  Improve customer retention

-  Enhance service quality

-  Support business growth

### Rationale for the Project

-  Reduce Customer Attrition: Identify key factors influencing customer churn and mitigate them.

-  Optimize Marketing and Service Plans: Develop targeted strategies for customer engagement.

-  Enhance Customer Experience: Ensure better service delivery.

-  Improve Financial Performance: Retain high-value customers.

-  Data-Driven Decision Making: Leverage analytics for informed strategies.

### KEY INSIGHTS

#### Statistical Analysis

**Missing Values:**

During the initial investigation into the data, I observed there are 11 missing values in Total Charges, all corresponding to customers with zero (0 month) tenure. This indicates that they are new customers who have not yet been billed their first monthly charge.

![Missing values](https://github.com/user-attachments/assets/c59cc735-d5d8-4226-a54e-0aeafa254e27)

![Missing values heat map](https://github.com/user-attachments/assets/392911ab-c3d1-4f02-b1f1-e7bf938f737c)


#### Categorical Data Insights:

**Customer Demographics & Service Preferences**

-  **Gender:** The dataset contains more male customers, but female customers have a higher churn rate.
-  **Marital Status:** A large proportion of customers have no partners, indicating possible marketing opportunities for family plans.
-  **Dependents:** Most customers have no dependents, suggesting a customer base that may value individual service packages over family bundles.
-  **Service Usage:** Almost all customers use phone services, but multiple service packages (e.g., internet + phone) are more common among long-term customers. Customers without phone services are less likely to stay long-term.

![Statistical Analysis1 ](https://github.com/user-attachments/assets/55f1dae7-17dc-46ce-b9bd-dea16e10bc8d)

### Visualization & Insights

### Univariate Analysis

**Tenure:** Majority of customers stay between **9-55 months**. The longer a customer stays, the higher their total charges, indicating that long-term customers are more profitable. The analysis also identified, many customers leave within the first 12 months, meaning early engagement is crucial for retention.

**Monthly Charges:** Ranges from $35 to $89, with customers paying higher amounts more likely to churn.

**Total Charges:** also ranges from $401 to $3,794, with some customers paying up to $8,000 or $6,000. This also reveals that customers leaving early tend to pay less total charges.

![box plot single](https://github.com/user-attachments/assets/06a3c14a-a4d2-422e-a2d1-d9a4cf3b78a0)

### Bivariate Analysis

**Gender:**

This analysis indicates that the system has more Male customers, but Female customers have a higher churn rate.

![gender visual](https://github.com/user-attachments/assets/9e7e9d61-5cf8-4b15-a88f-be926416a306)

**Contract Tenure**

A broader look into the contract types highlights the Month-to-month contracts have the highest churn. Customers with longer contracts stay longer. Most long-term customers stay between 19-55 months. The company should offer better deals for annual contracts and encourage migration from month-to-month plans. Longer tenure leads to higher total charges, but many customers do not stay long.

![Contract grade](https://github.com/user-attachments/assets/62d580a4-2a12-4f5f-9420-7d291f4401e4)

**Payment Method:**

According to this analysis, the Electronic check have the highest churn rate (1,071 customers). Electronic check is the most used payment method. Encourage other payment methods to reduce churn considering other payment methods (credit cards, bank transfers, mailed checks) show lower churn rates, likely due to ease of payment and auto-renewal features..

![Payment Method](https://github.com/user-attachments/assets/b7abc7bc-8a3c-4ead-af91-8c92881afa2e) | ![image](https://github.com/user-attachments/assets/b961daa3-998d-48a8-9ddc-e5237f120963)

Total charges increase with monthly charges. Longer tenure = higher total charges.

![image](https://github.com/user-attachments/assets/bcdc3ca0-4da8-4ea2-80fc-4a55f8fa9d64)

### Recommendations

**1. Reduce Early Churn (0-12 Months)**

-  Implement a customer onboarding program to increase engagement during the first year.
-  Provide special discounts or loyalty incentives for new customers who stay beyond 12 months.
-  Offer better customer support for new users to improve satisfaction and reduce early drop-offs.

**2. Encourage Long-Term Contracts**

-  Introduce discounted pricing or exclusive benefits for customers who switch from month-to-month plans to 1-year or 2-year contracts.
-  Provide a flexible upgrade option for month-to-month users to switch to longer contracts with minimal penalties.
-  Highlight the cost savings of longer contracts in marketing efforts to attract commitment.

**3. Improve Payment Options**

-  Reduce reliance on electronic checks, as this method correlates with the highest churn rate.
-  Encourage automatic bank payments or credit card auto-renewals to improve customer retention.
-  Offer incentives (discounts or cashback offers) for customers who switch to more stable payment methods.

**4. Customer Segmentation & Targeted Marketing**

-  Design tailored plans for female customers, as they show a higher churn rate despite making up a smaller portion of the customer base.
-  Develop marketing campaigns for customers without partners or dependents, as they form a significant portion of the user base.
-  Focus on long-term customers (49+ months) by offering loyalty rewards or service enhancements.

**5. Adjust Pricing Strategy**

-  Identify optimal price points that balance customer affordability with profitability.
-  Provide tiered pricing models that offer discounts for bundled services, making it more attractive to stay.
-  Offer promotional discounts for high-spending customers to prevent them from leaving due to cost concerns.

### Conclusion
By implementing proactive retention strategies, optimising payment structures, and offering stronger incentives for long-term contracts, Connectel can significantly reduce customer churn, improve financial stability, and drive long-term customer value.





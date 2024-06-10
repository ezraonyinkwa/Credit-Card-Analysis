# Credit-Card-Eligibility-Analysis

## Project Overview
The primary objective of this project is to analyze and identify key factors that determine the eligibility of applicants for credit card approval. 
### Data Sources
This dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/rohit265/credit-card-eligibility-data-determining-factors).The dataset contains customers details that are very crucial to determine the credit card eligibility of our customers.

###Tools

Excel
Power Query
Power Pivot - Data modelling
Power Point - Background layout
Conditional Formatting
Pivot Tables

#### Data Cleaning/Preparation

Data cleaning is a crucial step in preparing data for analysis. Using Excel, you can perform various data cleaning tasks to ensure your dataset is accurate, consistent, and ready for analysis.
The following are data cleaning processes that we carried out;
   - Standardizing data 
   - Removing Duplicates
   - Removing Nulls
     
#### Data Set
  
  ![Credit card formating](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/394ff495-79b4-40ef-a6e4-0cf16d31c07d)

#### Standardizing Data

Standardizing data is crucial in data cleaning process because it ensures data consistency across the dataset.
Facilitates accurate analysis and reporting. 

We created the age groups using the IF() formula.

![Age group credit card](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/d8f48144-0253-419f-add0-3ad5a8c343cd)


I rounded off the years employed.For the Income Type I used the PROPER() formula to make the first letter of the words capital letters

![Credit card standardizing data](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/bf48ec87-1b88-4d37-8e01-570a0530e85c)


#### Removing Duplicates

We checked for duplicates but no duplicates were found.

![Duplicates results](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/c6599692-54ee-4b68-baba-34403d807e24)

#### Checking for Nulls

Removing nulls in the data cleaning process is important because it prevents errors in analysis and calculations.
Ensures the completeness and reliability of the dataset.

In this section we utilised the CTRL+G to chec for nulls but there were no nulls found.

![Nulls excel](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/b9a683ae-0387-4601-a799-c8009d9c5c5d)



#### Data Modelling
To enhance our data analysis capabilities, we utilized Power Pivot to create data models. As part of this process, we created three additional tables: Customer Details, Family Details and Occupation Details, the credit card table was our fact table. By using the Customer ID as the primary key, we established relationships between these tables, allowing for comprehensive and integrated analysis of the data. This approach ensured a more organized and efficient data structure, facilitating deeper insights and more informed decision-making.

![Credit card data modelling](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/0783c7ab-cfdf-48fc-8b6c-3015719c4358)


#### Pivot Tables

We created pivot tables and applied conditional formatting to enhance data visualization and analysis.

![Pivot Tables](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/1e255f5c-5d6d-416b-86c6-4987d693b3a7)

### Analysis

#### KPIs

![Credit card KPIS](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/b691e5ee-0e45-4ad4-9da4-5eba6854483d)

#### Findings

These insights reveal that the total income of our customers stands at $1,759,544,541, with an average income of $181,228 across 9,709 customers. This substantial average income indicates that a significant portion of our customer base is likely to meet the income eligibility criteria for various credit card offerings

#### How long have customers created account with us
![Account Length](https://github.com/ezraonyinkwa/Credit-Card-Eligibility-Analysis/assets/139281995/71413d4f-9b8e-4ac2-b9e1-dd7cd3d83a13)

#### Findings

These insights indicate that most of our customers have an account length of 11 years, totaling 219 customers, followed by those with an account length of 13 years, totaling 216 customers. The lowest account length observed is 3 years, with 196 customers.

The longer account lengths suggest a stable and loyal customer base, which typically translates to higher creditworthiness. Customers with longer account histories are often seen as lower risk, making them more likely to be eligible for premium credit card products with higher limits and better benefits. On the other hand, customers with shorter account lengths may require more stringent eligibility checks.

#### What is the age group of most of our customers

![Age group credit card](https://github.com/ezraonyinkwa/Credit-Card-Eligibility-Analysis/assets/139281995/499c0f76-a4c2-4729-bdad-707e61dca0e6)


#### Findings

Majority of our customers fall within the age group of 35-44, comprising 2,701 customers, followed closely by the 25-34 age group with 2,480 customers. Conversely, the 18-24 age group represents the lowest number of customers at 209 individuals.
The higher representation in the 35-44 and 25-34 age groups suggests a demographic that is likely to have established financial stability and income levels conducive to creditworthiness. This makes them prime candidates for a range of credit card offerings, including those with higher credit limits and more extensive benefits.
However, it's essential to consider that younger customers in the 18-24 age group may have limited credit histories or lower incomes, impacting their eligibility for certain credit card products. 

#### What are the job position and which position has the highest average income.

![Average salary by position](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/fd54473a-7a0f-475c-aa8a-2599c54cb3ac)

#### Findings 

These insights from the top 10 highest-paying positions highlight significant salary disparities across job roles. Managers, with an average salary of $276,028, and Accountants, with an average of $203,420, represent positions with relatively high incomes. On the other hand, Medicine Staff, with a salary of $160,540, has a lower average salary among the top positions.
Individuals in higher-paying roles like Managers and Accountants are more likely to meet income requirements for premium credit cards with extensive benefits and higher credit limits. Their robust financial positions and stable incomes make them attractive candidates for such credit products.Individuals in lower-paying positions, such as Medicine Staff, may have lower credit card eligibility for premium offerings but may still qualify for standard credit cards tailored to their income levels.

#### What is the family status of our customers

![Family status](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/5076abaa-f273-414e-b669-96f6cac58e41)

#### Findings

A significant portion of our customers are married, totaling 6,530 individuals, followed by single/not married customers at 1,359 individuals. The widow category represents the lowest number of customers at 410.
Married individuals often have combined household incomes and shared financial responsibilities, potentially meeting income thresholds for premium credit card products. Their financial stability and dual-income sources can enhance eligibility for credit cards with higher limits and more extensive benefits.
Single individuals, while representing a substantial customer segment, may have varying income levels and financial commitments. Tailoring credit card offerings to suit their specific income and spending patterns can optimize credit card eligibility and meet their financial needs effectively.

#### What are the income types of our customers

![Income type of customers](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/0a9c4b66-9bb6-42f3-a729-1894c8677f6f)

#### Findings

 The majority of our customers are employed, totaling 4,960 individuals, while students represent the lowest customer segment with only three individuals.
 Employed individuals typically have stable incomes and financial obligations, making them prime candidates for various credit card products.Conversely, student customers, while representing a smaller segment, may have limited incomes and financial obligations. This could impact their credit card eligibility, particularly for premium offerings. 

 #### What is the level of education of most of our customers
 
 ![Level of education](https://github.com/ezraonyinkwa/Credit-Card-Analysis/assets/139281995/4a2d7ade-4dc0-4a7c-a9d5-b97b7372576f)

 #### Findings 
 
From the analysis, majority of our customers have an educational level of Secondary/Secondary Special, totaling 6,761 individuals, while only six customers have an academic degree as their highest education level.
Individuals with higher education levels, such as those with academic degrees, may have higher earning potential and financial literacy, potentially making them more eligible for premium credit card products with higher credit limits and exclusive benefits.
Customers with lower education levels, such as those with Secondary/Secondary Special education, may have varying income levels and financial responsibilities.

### Recommendations

-  Develop credit card products tailored to different educational backgrounds, marital statuses, and job roles. For example, offer credit cards with varying credit limits, rewards programs, and interest rates to cater to customers with diverse financial circumstances.
-  Implement financial education programs to improve financial literacy among customers, especially younger individuals and those with lower education levels. This can empower them to make informed financial decisions and manage credit responsibly, enhancing their eligibility for credit card products.
-  Offer credit-building credit card options for customers with limited credit histories or lower incomes, such as secured credit cards or starter credit cards. These products can help individuals establish or improve their credit scores over time, increasing their eligibility for higher-tier credit cards.
-   Develop customized eligibility criteria for credit card products based on age groups, marital statuses, and job roles. Consider factors like income stability, credit history, and debt-to-income ratios to determine eligibility accurately and fairly.
-   Implement risk assessment strategies to mitigate potential risks associated with credit card issuance, especially for younger customers or those with limited credit histories. This may include setting lower credit limits initially, monitoring credit card usage closely, and offering credit counseling services.







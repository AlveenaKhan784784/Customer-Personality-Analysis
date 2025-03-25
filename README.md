# Customer-Personality-Analysis
### Overview

**This project explores customer data to understand spending habits, campaign effectiveness, and customer segmentation. The analysis focuses on identifying trends and patterns in customer behavior using data preprocessing and exploratory data analysis (EDA).**

### Objective

- Analyze customer demographics and spending patterns.

- Identify which product categories are most popular.

- Investigate the relationship between income and spending.

- Assess the effectiveness of marketing campaigns.

- Explore how age, marital status, and family composition impact spending.

### Dataset:
- Source: [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- File Name: Customer Personality Analysis

- Separator: \t (Tab-separated values)

- Key Columns:

  - ID: Unique customer identifier

  - Year_Birth: Year of birth of the customer

  - Income: Annual household income

  - MntWines, MntMeatProducts, MntFishProducts, etc.: Spending on different product categories

  - AcceptedCmp1 to AcceptedCmp5: Whether the customer accepted past campaigns

  - Response: Response to the latest campaign

 ### Data Preprocessing

- Handled missing values.

- Identified and treated outliers using IQR and domain knowledge.

- Created new features such as the spending-to-income ratio.

### Exploratory Data Analysis

- Spending Trends: Analyzed average spending per customer and spending behavior across different income groups.

- Popular Products: Determined which product categories had the highest sales.

- Campaign Effectiveness: Evaluated which campaigns had the highest acceptance rates.

- Demographic Insights: Analyzed how factors like age, marital status, and family composition impact spending.

### Key Insights from Customer Personality Analysis

1️⃣ **General Spending Trends**
- The average spending per customer varies significantly, with some customers spending a large portion of their income.
- Wines are the most popular product category, followed by Meat and Fish purchases.
- A small group of high-income customers contributes to the majority of total spending, while some low-income customers exhibit unexpectedly high spending behavior.

2️⃣ **Income vs. Spending Behavior**
- Customers with higher incomes generally spend more, but there are exceptions where low-income customers spend disproportionately high amounts.
- A few customers have zero or very low income but high spending, which may indicate data inconsistencies or alternative income sources.
- The spending-to-income ratio helps identify over-spenders, who might be spending more than they can afford.

3️⃣ **Campaign Effectiveness & Customer Engagement**
- Campaign response analysis shows that some campaigns were significantly more successful than others.
- 462 customers responded to at least one campaign
- Most successful campaign: AcceptedCmp4
- A moderate positive relationship between total spending and campaign acceptance. This means:

    - Customers who spend more tend to accept more campaigns.

    - However, it's not a very strong correlation, meaning other factors also influence campaign acceptance.

4️⃣ **Age & Marital Status Influence on Spending**
- Young ones are spending more than Middle-aged and senior
- Single are spending more

### Tools & Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)

- Jupyter Notebook for analysis

- Data Preprocessing Techniques: Handling missing values, outlier detection (IQR), feature engineering.

### Conclusion

**This project provides valuable insights into customer spending habits, marketing effectiveness, and potential business strategies. The findings can help businesses optimize marketing efforts and improve customer engagement.**

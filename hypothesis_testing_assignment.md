# Hypothesis Testing Assignment
## Data Visualization with Matplotlib & Seaborn - Module 2

**Dataset:** Module 2 Lesson 1 Dataset
**Variables:** Customer Age, Gender, Annual Income (USD), Purchase Amount (USD), Product Category

---

## Prompt 1: Age and Spending Patterns

**Prompt:**
Is there a relationship between a customer's age group and how much they spend per purchase? In other words, do customers in different age brackets (18-25, 26-35, 36-45, 46-55, 56+) tend to spend different amounts on average?

**Null Hypothesis (H₀):**
Customer age does not affect average purchase amount. There is no statistically significant difference in the mean purchase amount across the different age groups (18-25, 26-35, 36-45, 46-55, 56+).

**Alternative Hypothesis (H₁):**
Customer age does affect average purchase amount. There is a statistically significant difference in the mean purchase amount across at least two of the age groups.

**Explanation:**
This hypothesis test would help determine whether age is a meaningful factor in customer spending behavior. If we reject the null hypothesis and find that age groups differ in their purchase amounts, a business could use this insight to create age-targeted marketing campaigns, adjust pricing strategies for different demographics, or develop product recommendations tailored to specific age segments. For example, if younger customers (18-25) spend significantly less per transaction, a company might offer smaller package sizes or budget-friendly options to this demographic. An ANOVA test would be appropriate here since we are comparing means across more than two groups.

---

## Prompt 2: Gender and Product Category Preferences

**Prompt:**
Is there an association between a customer's gender and the type of product category they prefer to purchase? Do customers of different genders (Male, Female, Non-binary) show different patterns in their product category choices (Apparel, Beauty, Electronics, Groceries, Sports)?

**Null Hypothesis (H₀):**
There is no association between gender and product category preference. Gender and product category are independent variables, meaning the distribution of product category purchases is the same across all gender groups.

**Alternative Hypothesis (H₁):**
There is an association between gender and product category preference. Gender and product category are not independent, meaning customers of different genders show significantly different patterns in their product category choices.

**Explanation:**
This hypothesis test would help determine whether product preferences vary by gender. If we find a significant association, businesses could use this information to make data-driven decisions about inventory management, store layout, targeted advertising, and personalized product recommendations. For example, if female customers show a stronger preference for Beauty products while male customers prefer Electronics, marketing teams could tailor their campaigns accordingly. A chi-square test of independence would be appropriate here since both variables (gender and product category) are categorical.

---

## Prompt 3: Income and Spending

**Prompt:**
Is there a relationship between a customer's annual income and the amount they spend per transaction? Specifically, do customers with higher annual incomes tend to make larger purchases?

**Null Hypothesis (H₀):**
There is no relationship between annual income and purchase amount. The correlation between annual income and purchase amount is zero (or not significantly different from zero). Higher-income customers do not spend more per transaction than lower-income customers.

**Alternative Hypothesis (H₁):**
There is a positive relationship between annual income and purchase amount. The correlation between annual income and purchase amount is significantly greater than zero. Higher-income customers tend to spend more per transaction than lower-income customers.

**Explanation:**
This hypothesis test would help determine whether income level is a predictor of spending behavior. If we find a significant positive relationship, businesses could use income as a factor in customer segmentation strategies, develop tiered product offerings (budget vs. premium lines), or focus high-value marketing efforts on higher-income customer segments. Conversely, if no relationship exists, it would suggest that purchase decisions are driven by factors other than income, prompting businesses to investigate other variables. A Pearson correlation test or simple linear regression would be appropriate here since both variables (income and purchase amount) are continuous.

🛍️ Customer Sales Analysis

Exploratory data analysis (EDA) of an online retail dataset from India. The project looks at who the customers are, where they are located, and what they buy, using visualizations built in Python.
This EDA also explores customer demographics (age, gender, state) and purchase Amount to show who the customers are, where they are, and how much they spend. The findings can guide targeting and marketing decisions.




🎯 Objectives

 Understand customer demographics (age, gender, marital status, occupation sector)

 Identify top-performing states and zones by orders and total amount

 Find the most popular product categories

 Highlight growth opportunities and risks for the business

 



🧰 Tech Stack

 Python
 Pandas, NumPy
 Matplotlib, Seaborn
 Jupyter Notebook



📈 Analysis Covered

Visualization	Insight

 Age-group wise marital status count   : Singles outnumber married customers in every age group
 
 Count of sectors in each age group    : 26-35 is the largest group
 
 Gender and zone wise count            : Women outnumber men in every zone
 
 Total orders in each product category : Clothing, Food and Electronics lead
 
 Sector wise total amount              : IT, Healthcare, Aviation and Banking spend the most
 
 Sectors with total users              : IT Sector has the most users (1,588)
 
 State wise total amount               : Uttar Pradesh leads, Telangana is lowest
 
 Top 10 states by orders               : Uttar Pradesh (4,813), Maharashtra (3,811), Karnataka (3,241)
 
 Total orders in each age group        : 26-35 contributes about 41% of orders
 
 Zone wise users                      : Central zone has about 38% of users

  Scatter (Age vs Amount)             :   Check for a relationship between age and spend

  Histogram + KDE (Age)               :   Understand the age distribution

  Box plot (Amount)                   :   Show spread, median and outliers in spending

  Heatmap (State × Gender)           :   Compare customer counts by region and gender




🔑 Key Findings

Core customer: A single woman aged 26-35, working in IT, Healthcare, Aviation or Banking.

Top locations: Uttar Pradesh, Maharashtra, Karnataka and Delhi lead in orders and revenue. The Central zone has the most users (~38%) and the Eastern zone the fewest (~7%).

Top categories: Clothing & Apparel, Food, and Electronics & Gadgets.

Risk: Sales depend heavily on a few states, age groups and categories.

Opportunity: Grow the Eastern zone, male customers, the 46+ age groups, and weak sectors such as Agriculture and Textile.

Age is concentrated in the late 20s to mid 30s. The distribution peaks at roughly 28 to 32 and is right-skewed. Counts drop sharply after about 56, and customers over 60 are sparse (under about 50 per bin).

Age has no visible effect on spending. The scatter plot shows the same horizontal bands at every age, so age alone does not predict Amount.

Amount clusters at discrete levels. Bands near ₹2k, 5k, 8k, 12k, 16k and 19–23k suggest fixed price points or product tiers, not a continuous spread.

Spending is moderately right-skewed. The median is about ₹8,100 and the IQR runs from roughly ₹5,400 to ₹12,700. A few high-end outliers sit above about ₹23,500, and there are no low outliers.

Women are the dominant group. They outnumber men by roughly 2 to 3 times in every state.

Treat the 55+ segment as under-served, or check whether the drop reflects data collection limits.




✅ Recommendations

Target the 26-35 age group with campaigns for clothing, food and electronics.

Invest in marketing in the Eastern zone and in under-performing states such as Gujarat, Rajasthan and Telangana.

Build campaigns for male customers and the 46+ age groups.

Review low-performing categories and sectors to decide whether to promote or phase them out.




✅Limitations and Next Steps

The four plots describe the data but do not yet explain the spending bands or the drop after age 56.

Check why the data thins out sharply after about 56 (binning, sampling, or real behavior).

Compare Amount distributions by gender and state, not just counts.

Add age groups (12–17, 18–25, 26–35, 36–55, 55+).

Analyze product category, occupation or marital status if available.

Run a correlation or hypothesis test (for example ANOVA) on Amount across gender and state.




📊 Visualizations


1. Gender and Zone wise Count

<img width="1337" height="577" alt="gender_zone_wise_count" src="https://github.com/user-attachments/assets/92b229de-4697-4b3e-ba15-870ae7ebc93d" />


2. Zone wise Users

   <img width="534" height="507" alt="zone_wise_users" src="https://github.com/user-attachments/assets/8ee1e76d-3826-4152-b1c9-db49f748d794" />

3. Total Orders in Product Categories

   <img width="1270" height="684" alt="productcategory_wise_totalorders" src="https://github.com/user-attachments/assets/77d6d4e5-605f-4e5d-995d-61e5c3535dbe" />

4. Age-Group wise Marital Status Count

   <img width="1228" height="530" alt="agegroup_wise_maritalstatus_count" src="https://github.com/user-attachments/assets/2d292ea0-f3b1-4813-aa51-dd15fdc64136" />

5. Total Amount by each Sector

   <img width="1214" height="607" alt="sector_wise_totalamount" src="https://github.com/user-attachments/assets/493541cd-a7aa-4adf-b211-d0fcacb4c76e" />

6. Top 10 states with maximum Orders

   <img width="1228" height="618" alt="states_with_maxorders" src="https://github.com/user-attachments/assets/6a56b5d9-4f08-4822-af5d-d45878b80bcd" />

7. Total Amount by each State

   <img width="1455" height="618" alt="state_wise_totalamount" src="https://github.com/user-attachments/assets/023ca99c-b27e-44d5-b38c-5e29d2dac881" />

8. Total Orders in each Age-Group

   <img width="469" height="430" alt="totalorders_in_each_agegroup" src="https://github.com/user-attachments/assets/716c8710-96cc-4696-b28b-5b78cb704f7a" />

9. Count of Sectors in each Age-Group

    <img width="1228" height="530" alt="count-of-sectors_in_each_agegroup" src="https://github.com/user-attachments/assets/17498c29-fcca-42f8-929b-a2cb39ea1253" />

10. Sectors with it's Total Users

    <img width="1228" height="607" alt="sectors_with_totalusers" src="https://github.com/user-attachments/assets/e6869b97-e5ec-419b-a15f-3802c12d2773" />

11. HIST PLOT (AGE COUNT)

<img width="581" height="432" alt="age_count" src="https://github.com/user-attachments/assets/df4675ac-d4ee-4fd8-9bc8-31f5447b71ba" />

12. BOX PLOT (AMOUNT)

<img width="1203" height="525" alt="amount_boxplot" src="https://github.com/user-attachments/assets/2a007672-e654-44b4-bfb3-82769fe5ce53" />

13. SCATTER PLOT (AGE vs AMOUNT)

<img width="1024" height="527" alt="age_amount_scatter" src="https://github.com/user-attachments/assets/7f43c370-9b03-49ad-b4d8-2721689d13fd" />

14. PIVOT TABLE

<img width="663" height="433" alt="pivot_table" src="https://github.com/user-attachments/assets/0e5e0a73-1c2d-4a9c-8fcc-3a3e0bb2b140" />









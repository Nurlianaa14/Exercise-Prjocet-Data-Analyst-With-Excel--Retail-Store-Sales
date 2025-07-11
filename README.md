# Exercise | Prjocet Data Analyst With Excel - Retail Store Sales

## Data Cleaning
1. Standardizing format: Ensure uniform date, time, and numeric format for consistency
2. Validating data: Apply checks for errors, such as valid emails and proper spelling
3. Removing duplicates: Eliminate duplicate entries to maintain data integrity
4. Handling missing values: Fill gaps using imputation, interpolation, or appropriate removal
5. Correcting incosistencies: Fix variations is spelling, capitalization, or data entry errors 

## Data Processing
1. Merging tables: Combine datasets using keys to create a unified view of the data
2. Creating calculated columns: Add new columns derived from formulas and logical operations
3. Applying VLOOKUP: Link related data across tables to enrich the datasetwith relevant information
4. Filtering and sorting: Organize data to focus on relevant subsets and insight

## Data Analyst
1. Descriptive statistics:
   
   a. Perform a comprehensive statistical summary to uncover key patterns and trends in the dataset
   
   b. Indetify outliers and distributional properties to ensure data consistency and reliability before further analysis
   
3. Hypothesis Testing Using t-test
   
   Conduct a two sample t-test to evaluate the statistical significance of differences between two groups or conditions based on the clients business question
   
   Scenario: Whether there is relationship between delivery time and order status (Completed | Returned)
   
   H0      : Delivery time does not affect whether an order is returned.
   
   H1      : Orders with longer delivery times are more likely to be returned.

   Based on the results of the t-Test: Two-Sample Assuming Unequal Variances, the p-value (P(T<=t) two-tail) was found to be less than the alpha level of 0.05.
   
   Therefore, the alternative hypothesis (H1) is accepted. This indicates a significant difference between the average delivery time of returned orders and completed orders.
   
   In other words, delivery time has an impact on order status.
   
   As an insight, it is recommended to monitor orders with a delivery time of more than 7 days. This is intended to reduce the risk of product returns due to delivery delays.

## Data Collection
1. Design form: Create the input form, lock non-input areas, designate writable fields
2. Set up VBA: Write a VBA macro to handle form submission and move data to the database
3. Auto populate and store data: Automatically calculate fields and store data in the database
4. Confirm and reset: Show a confirmation pop up and reset the form new data entry 

## Data Visualization/ Dashboard
1. Create KPI in pivot tabel: Design the pivot table to calculate key perfomance indicators(KPIs)
2. Design framework: Plan the layout and structureof the dashboard on paper, then replicate it in excel
3. Create chart: Add the necessary chart to visualize the KPIs and data insight
4. Add slicers: Insert slicer for interactive filtering of data within the dashboard

## Business Insight

Sales from January 2024 – December 2025

<img width="759" alt="image" src="https://github.com/user-attachments/assets/8ec0d8d2-3479-49a6-90a4-23ff05ddb4e1" />


1. 📈 KPI
   - Sales Revenue: $775,526
   - Total Cost: $503,933
   - Net Profit: $271,593
   - Total Orders: 561
     
   💡 Profit margin remains stable despite intense competition and fluctuating sales throughout the year.

2. 📅 Monthly Sales Trends
   - Highest sales occurred in December – likely due to year-end promotions
   - February, March, May, and September tend to be lower – these can be areas of improvement
     
   💡 Design promotional strategies for months with lower sales.Design seasonal promotional campaigns, limited-time discounts, or new product launches specifically for these months to stimulate demand.

3. 🌎 Geographic Performance
   - Nigeria and Australia dominate global revenue
   - Countries such as China and the United Kingdom (UK) show growth potential
     
   💡 To drive growth, the company can focus on expanding into high-potential or niche markets, including Brazil and even unconventional regions like Antarctica.

4. 🛍️ Category Analysis
   - Books and Electronics contribute the most to revenue
   - Apparel and Groceries are stable and cost-efficient
   - Home Decor is the lowest-performing category
     
   💡 Prioritize product development and campaigns in high-profit categories. Reevaluate the Home Decor category – consider rebranding, bundling, or even discontinuation if the profit margin is too low.

5. 💳 Payment Method Insight
   - Customers prefer Bank Transfer (30%) and Mobile Money (26%)
   - Cash (21%) is relatively low — reflecting good digital adoption
     
   💡 Ensure digital payment system integration remains optimal.

6. 📅 Daily Revenue Trends
   - Wednesday and Friday have the highest daily revenue
   - Tuesday is the slowest — a good time for customer education or promotions
     
   💡 Schedule promotional launches or product education campaigns on Tuesdays to boost engagement. Leverage Wednesdays and Fridays as peak days with exclusive offers.

7. 🚨 Order Completion & Returns
   - 52% of orders are completed, while 48% are returned — a very high rate
     
   💡 Evaluate product quality and the shipping process, ensure product descriptions on sales platforms are accurate, and improve customer service to reduce dissatisfaction that leads to returns.


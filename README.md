##### E-Commerce-Dashboard
A detailed analysis of a synthetic dataset to analyze sales trends, customer demographics. referrals efficiency ang geographical preferences.
#### Project Overview
This synthetic dataset gave me the opportunity to perform various analysis to leverage data-driven insights to enhance customer satisfaction, optimize product offerings, and improve marketing strategies by understanding product performances, sales trends, referrals efficiency, demographic and geographical preferences across the year 2021 and January 2022.
#### Problem Statement
The objective of this project was to analyze and derive insights to uncover patterns in customer behavior, product performance, and referral sources. By addressing the following key questions, we aim to provide actionable recommendations to optimize sales, improve customer satisfaction, and refine marketing strategies:
- Product Performance Analysis: Identify which product item or category received the best and worst reviews, enabling the business to understand customer preferences and dissatisfaction areas.
- Sales Trends: Determine the products with the most and least sales over the years to pinpoint high-performing items and underperforming ones, guiding inventory and promotional decisions.
- Referral Source Effectiveness: Analyze the referral sources to find out which platform or channel drives the highest traffic and sales conversions, helping allocate marketing efforts more effectively.
- Customer Demographics and Purchasing Behavior: Examine customer demographics, particularly gender, to identify purchasing trends and determine which gender is responsible for the highest and lowest purchases across different product categories. This insight will help in tailoring product offerings and marketing campaigns to target specific customer groups.
- Geographical Sales Insights: Identify the country with the most sales to understand the geographical distribution of the business's customer base and target markets.
### Data Cleaning Process
- Duplicate Values: I began by inspecting the dataset for duplicate rows. After performing this check, I discovered that there were no duplicate entries. This showed that the dataset was clean in terms of unique records.
- Missing Values: I checked for missing values throughout the dataset. Fortunately, there were no missing entries, so no imputation or removal was needed in this regard.
- Aligning Products with Categories Using VLOOKUP: I noticed discrepancies where products were not aligned with their appropriate categories. To resolve this, I used the VLOOKUP function to assign each product to its appropriate category. This step ensured the integrity of product-category relationships and improved the dataset's reliability.
- Formatting Price and Total Amount Columns: The "Price" and "Total Amount" columns needed attention to ensure all values were properly formatted as currency. I ensured that every cell had accurate values with the correct currency symbol (e.g., $2,288), improving clarity and presentation.
- Correcting Review Scores and Texts: I observed that the review scores and corresponding review texts were misaligned. To fix this, I rounded up the review scores to the nearest whole number and used the IF function to match the scores with accurate review texts. This adjustment ensured consistency and accuracy in the customer feedback data.
### Insights
![Screenshot (21)](https://github.com/user-attachments/assets/d85ae516-f540-4f48-92ce-d3d3fae4cefc)
### Recommendations
After carefully displaying sales trend through visualizations on the E-commerce dashboard, it is first of all observed that the products, geographical sales, referral sources, monthly sales and customer demographics are doing well in generating revenue for the company because there isn’t a significant difference in how each of them perform. However, certain improvements can still be made in the following ways:
-	Increase production: The most popular product category should never be out of stock and always available for purchase across different regions
-	Enhance Marketing Strategy: this process is essential to both categories that are over and underperforming in a company. Digital marketing and social media have to be effectively utilized to target the right audience.
-	Assessment of Customer Reviews: this is essential so as to gather insights from customers to understand why the product is popular or least desired. This helps to deeply analyze their opinions on the products quality, price, convenience and unique feature
-	Enhancement of products: All products in a company that performs the best and least needs to be improved on its design, functionality and features based on customer needs.


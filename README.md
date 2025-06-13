# E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT
The report is an e-commerce sales Dashboards which gives which show full analysis of the sales trend by each customers and given predictions about the companies growth 

       # BACKGROUND IMAGE ON IS ON IS WAY
       
## Introduction 
In today’s competitive digital marketplace, understanding customer behavior and
sales performance is critical for driving revenue, improving retention, and optimizing
marketing strategies. This Power BI Analytical Dashboard provides a comprehensive
view of key e-commerce metrics, enabling data-driven decisions to enhance profitability
and customer experience.

### Dataset Description:

The dataset consists of four interrelated tables, providing a comprehensive view of customer
behavior, sales transactions, product details, and website activity for an e-commerce platform.
Each table plays a key role in analyzing business performance and customer engagement.
 1. Customers Table:
Contains demographic and profile information of customers. Fields include Customer ID,
Name, Email, Gender, Country, Registration Date, Age, and User Tier.
(5,000 records)
 2. Orders Table:
Provides detailed information on all customer purchases. It includes Order ID, Customer
ID, Order Date, Order Status, Product ID, Quantity, Unit Price, and Total Amount
(calculated as Quantity × Unit Price).
(20,000 records)
 3. Products Table:
Contains the product catalog data, with each record representing a unique item in the store.
Fields include Product ID, Product Name, Category, Sub-Category, and Price.
(50 records)
4. Website Traffic Table:
Captures user activity and behavior on the website. Fields include Visit ID, Customer ID,
Visit Date, Page Visited, Time Spent, Device Used, and Traffic Source.
(100,000 records)

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-02%20124703.png)

 The Entity-Relationship Diagram (ERD) above illustrates the key relationships among
the tables. There is a one-to-many relationship between Products and Orders, linked via
ProductID. Similarly, a many-to-one relationship exists between Orders and Customers,
connected through CustomerID. Additionally, there is a one-to-many relationship
between Customers and the Website_Traffic table, also joined by CustomerID.

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-11%20140732.png)

The dashboard above provides a high-level summary of e-commerce sales performance and customer
behavior. It highlights key metrics such as the total number of customers (5,000) and a total revenue of
$41.47 million. Out of approximately 20,000 registered users, 4,919 customers successfully placed
orders across 50 available products in the store. The data spans the period from April 28, 2023 to April
27, 2025, and includes customer activity across multiple distinct countries.
  To gain deeper insights, the dashboard is divided into five key sections, each offering a focused
analysis of different aspects of the business:
    1. Sales performance Dashboard
    2. Customer behavior analysis Dashboard
    3. Website Traffic and conversion Funnel Dashboard
    4. Products Insight Dashboard
    5. Forecast Dashboard.

### Objectives of the Dashboard

  1. Analyze e-commerce sales and customer behavior to uncover key trends.
  2. Measure business performance using key metrics and visual dashboards.
  3. Track new vs. returning customers over time.
  4. Forecast future sales using time series models.
  5. Identify customers at risk of churn and understand churn patterns.
  6. Evaluate customer retention rate and cohort activity.
  7. Support data-driven decisions that improve customer engagement.
  8. Increase revenue by targeting high-value customer segments.
  9. Optimize marketing strategies based on behavioral insights

## Sales performance Dashboard

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-11%20140826_1.png)

   The Sales Performance dashboard presents a detailed analysis of market activity,
highlighting a total revenue of $41.47M generated from 20,000 orders, resulting in an average
order value of $2.07K (calculated as Total Revenue / Total Orders).
 Sales growth trends show a notable increase in revenue between 2023 and 2024, followed
by a significant decline of approximately $13.9M from 2024 to 2025.
In terms of Customer Lifetime Value (CLV) by User Tier, the Bronze tier accounts for the
highest CLV at 34.02%, followed by Silver (33.47%), and Gold (32.71%).
 The Age Group Distribution indicates the highest number of orders from customers aged
59–68, while those aged 69 and above contribute fewer orders—potentially due to lower
digital engagement in older age brackets.
 Analyzing CLV by Month, July records the highest customer value, driven primarily by
purchases in the Living Room category, with a focus on Clothing.
 Regarding Customer Lifetime, 41.28% of customers have remained active for 3 years,
39.34% for 2 years, and 19.26% for 1 year, showing strong long-term retention.
Lastly, the Product Quantity analysis reveals that Sneakers are the top-selling item with 1,343
units sold, while Headphones have the lowest sales at 1,066 units.

###  Recommendation:

1. Focus Marketing on Bronze Tier Customers
Since Bronze users generate the highest Customer Lifetime Value (CLV) (34.02%), introduce
loyalty rewards, upsell campaigns, or exclusive offers to retain and upgrade them into higher
tiers.
2. Address the Drop in Revenue (2024 → 2025)
The dashboard shows a $13.9M revenue drop—conduct a product/category-level deep dive to
understand the cause. Reintroduce top-performing SKUs or run promotional campaigns during
the same weak months.
3. Expand Successful Product Lines
Sneakers are the top-selling item in terms of quantity—consider increasing inventory, launching
complementary accessories, or bundling offers around this product to maximize conversions.
4. Target Younger & Middle-Age Demographics
Majority of sales come from customers aged 59–68 and 49–58. Create tailored campaigns for
under-performing age groups (e.g., 18–28) to diversify the customer base and secure long-term
growth.
5. Retain Long-Term Customers through Engagement
With 80% of users staying 2–3 years, maintain engagement through email campaigns, loyalty
points, or feedback surveys. Prioritize users nearing the 1-year mark to improve retention before
churn risk rises.

## CUSTOMER BEHAVIOR ANALYSIS 

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-11%20140853.png)

From the customer behavior analysis, we observed that 5,000 users registered on the platform, and out
of these, 4,919 customers placed at least one order. When comparing new vs. returning customers, we
found a 1:3 ratio, with approximately 4,926 new customers and over 15,000 returning customers —
which includes users who made repeat purchases after their initial order.
In the churn analysis, we identified that 62.28% of users are churned, meaning they haven't
made a purchase in the last 90 days. Additionally, 1.62% of users registered but never
completed an order.
The retention analysis shows a strong retention rate of 92.7%, indicating that a large proportion
of customers continue to engage and make purchases over time.
Analyzing the customer tier distribution, we found that Silver-tier customers have the highest
order volume at 1,718 orders, followed closely by Gold-tier with 1,684 orders, and Bronzetier with 1,598 orders.
 Finally, our monthly customer trend charts — including Total Customers by Month and New
vs. Returning Customers by Month — provide a clear view of customer growth and engagement
patterns over time.

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-06%20075944.png)

The higher the Returning customer and the new customer at the same Month the higher
number of customer for that Month. August had the highest customer count (1,741), followed
by July (1,730), driven by strong new and returning customer activity. In contrast, February saw
fewer total customers (1,540) despite having many returning users (1,362), indicating lower
new customer acquisition that month.

### Recommendation:

1. Re-engagement Campaigns for Churned Users
 With over 62% churned customers, implement personalized email or SMS campaigns
offering discounts, loyalty points, or product recommendations to re-engage inactive
users.
 Use predictive churn scores to target users most likely to return with the right incentive.
2. Onboarding Journey for First-Time Users
 Since 1.62% of users never placed an order, improve the onboarding process by
offering guided tours, welcome offers, or reminder nudges to help users complete their
first transaction.
 Highlight benefits of placing the first order (e.g., free delivery, points, or discounts).
3. Loyalty Program Optimization
 With Silver-tier customers driving the highest volume, consider offering exclusive
benefits or early access to promotions to encourage retention and upsell them to Goldtier.
 Introduce tier progression incentives (e.g., “Spend $X more to reach Gold”).
4. Strengthen Retention Channels
 Maintain the 92.7% retention rate by continuing to deliver value through timely offers,
excellent service, and personalized product recommendations
 Monitor monthly retention by cohort to identify early signs of engagement drop-off.
5. Customer Growth Tracking
 Regularly monitor New vs. Returning Customers and customer acquisition cost (CAC) vs
lifetime value (LTV) to evaluate the effectiveness of marketing efforts.
 Allocate more budget toward channels that bring high-LTV returning users.
6. Data-Driven Personalization
 Leverage behavioral data (purchase frequency, value, category preference) to personalize
marketing messages and product suggestions for each customer segment.
7. Boost new customer acquisition during months like February by increasing marketing campaigns or
promotions, while maintaining efforts that keep returning customers engaged.

# WEBSITE TRAFFIC AND CONVERSION FUNNEL DASHBOARD

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-11%20140934.png)

We have a total of 5 distinct websites, which collectively recorded 100,000 visits. The bounce
rate is 100%, indicating that each user visited only one page before leaving, with no further
interaction.
Traffic to the websites came from four main sources: Organic Search, Paid Ads, Referrals, and
Social Media. Among these, Social Media had the highest impact, driving 25,096 visits,
followed by Organic Search, Paid Ads, and Referral traffic.
Analyzing the conversion funnel (Visitors → Add to Cart → Checkout → Completed Order), we
observe that:
     19,947 users added items to their cart
     20,036 proceeded to checkout
     20,037 completed their orders
Interestingly, the number of users who checked out and completed their orders is slightly
higher than those who added items to their cart. This may indicate user behavior where some
skipped the "add to cart" step or completed orders from previous sessions.
Comparing the total number of visitors (100,000) to the number of users who added items to
their cart (19,947), there is a significant drop-off of 80,053 users at the initial stage of the
funnel.
In summary, out of 100,000 site visitors, only about 20,000 completed purchases, highlighting
potential areas for improvement in user engagement and conversion.

### Recommendation

1. Reduce Bounce Rate
    Make your website more interesting and easy to use.
    Add clear buttons to guide visitors on what to do next.
    Show content that matches what people are looking for.
2. Get More People to Add Items to Cart
    Show discounts and promotions clearly.
    Make sure product pages have enough details and good pictures.
    Remind users about items when they try to leave the page.
3. Improve Checkout and Order Completion
    Make checkout quick and easy.
    Offer many payment options (e.g. card, bank transfer, wallet).
    Send reminders to users who left items in their cart.
4. Use Social Media More
    Spend more on ads where most visitors come from (like Facebook or Instagram).
    Work with influencers to bring in more people.
    Show ads again to people who visited but didn’t buy.
5. Improve Other Traffic Sources
    Make your site easier to find on Google (SEO).
    Make your paid ads better and more focused.
    Create a referral program so happy customers invite others.
6. Keep Tracking and Testing
    Watch where people drop off in the buying process.
    Try different designs and messages to see what works best.
    Check reports regularly and make changes based on the data

#    PRODUCTS INSIGHT DASHBOARD

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-11%20141053.png)

From the products insight dashboard; it shows that we have a Total revenue of $41.47M which
was from 50 Products. The Total revenue by category show the breakdown of the revenue
showing the category with their revenue Electronics $12.2M, Furniture $12.0M, Clothing
$11.3M, and Accessories $5.9M. India is the country with the highest revenue with USA being
the lowest revenue with $5.48M.
### Countries with Revenue ranking and categorical revenue details
1. India ($6.61M): This has the highest revenue which they deal more with Electronics
($2.01M) (i) Furniture ($1.82M), (ii) Clothing ($1.82M), (iii) Accessories ($0.95M).
2. Germany ($6.06M): They deal more with Electronics ($1.78M) (i) Furniture
($1.73M), (ii) Clothing ($1.68M), (iii) Accessories ($0.88M).
3. Canada ($6.01M): They deal more with Electronics (1.81M) and Furniture ($1.79M)
but not much difference with Clothing ($1.63M) and very less of accessories which is
$0.78M.
4. France ($5.91M): They deal more with Electronics ($1.81M) (i) Furniture ($1.70M),
(ii) Clothing ($1.53M), (iii) Accessories ($0.86M).
5. Australia ($5.71M): They deal more with Electronics ($1.67M)  Furniture
($1.65M), (i) Clothing ($1.61M), (ii) Accessories ($0.78M).
6. UK ($5.7M): They deal more with Electronics ($1.68M) (i) Furniture ($1.60M),
(ii) Clothing ($1.60M), (iii) Accessories ($0.82M).
7. USA ($5.48M): They deal more with Electronics ($1.69M) i Furniture ($1.58M),
(ii) Clothing ($1.41M), (iii) Accessories ($0.79M).
### Recommendation:
The cloth with the highest purchase is Jeans 14 with a revenue of $1.9M lowest is Bookshelf 18
with revenue of $26k. Also looking at the returning rate the product with the highest returning
rate is Sofa 27 Furniture where Furniture has the highest returned products which is 16
products followed by Electronics has 15 returned products then, Clothing 12 returned
products and Accessories 7 returned products.

# FORECAST DASHBOARD 

![](https://github.com/Ebenezer080925/E-COMMERCE-SALES-AND-CUSTOMER-BEHAVIOUR-ANALYTICAL-REPORT/blob/main/Screenshot%202025-06-11%20153210.png)

The Forecast Dashboard focuses on future performance predictions, providing visual insights into
the company’s projected growth. The first chart, Total Amount by Month, displays the revenue
generated each month. Users can explore specific months using the Date slicer. July recorded the
highest revenue at $3.7M, while February had the lowest at $3.2M.
Note: The dark grey bars represent actual values, while the light grey bars indicate forecasted values.
The light grey section of the chart forecasts a decline in revenue for next year's February, with expected
earnings between $3.1M and $3.5M.
The Total Customer ID by Country and Churn Prediction chart highlights the number of customers in each
country and their churn status — where 0 = Not Churned and 1 = Churned.
From the data:
India, despite having the highest revenue earlier, also has the highest number of churned customers
(513).
USA has the lowest number of churned customers (422).
France leads in Not Churned customers (278), while Australia has the lowest (238).
Finally, the Churn Prediction by Country chart compares the churn rates across countries. India has the
highest churn rate at 16.47%, while the USA has the lowest at 13.52%.
###  Recommedation 
1. Investigate why churn is highest in India despite strong sales — factors such as service
  quality, follow-ups, or competitive offers could be influencing customer loss.
2. Implement retention strategies during low-revenue forecast months, such as February,
  by launching promotions or engagement campaigns.
3. Focus on markets with high churn percentages for customer satisfaction surveys or
  loyalty programs.
### Conclusion:
This e-commerce sales and customer behavior analysis highlights key opportunities to drive
growth and improve customer retention. With $41.47M in revenue and 5,000 customers, the
data reveals:
i Bronze-tier customers contribute the highest CLV (34.02%), making them a prime target
for loyalty programs.
ii Churn remains a challenge (62.28%), especially in high-revenue markets like India,
requiring targeted re-engagement strategies.
iii Website optimization is critical, with an 80% drop-off before cart addition and a 100%
bounce rate indicating UX improvements are needed.
iv Forecasts predict a revenue decline in early 2025, urging proactive promotions and
inventory adjustments.
By focusing on high-value customer segments, reducing churn, and enhancing conversion
funnels, the business can unlock sustained revenue growth and customer loyalty.






# Vrinda_Clothing_Sales_Dashboard_2022
This Excel-based retail analysis examines Vrinda Clothing Store’s sales data to uncover customer trends, popular product categories, and seasonal performance. Using PivotTables and dashboards, it reveals the key drivers behind the store’s revenue growth and operational success.



<img width="1850" height="800" alt="VRINDA STORE DASHBOARD" src="https://github.com/user-attachments/assets/5f0acc50-6bb2-41ed-be62-4e745bcaefdd" />



**1. Introduction**

   Objective of the Project 

The main objective is to analyze Vrinda Clothing Store’s sales data to understand performance 
across gender, product categories, age groups, and delivery channels. The project seeks to 
identify which segments, states, and product lines drive the highest revenue and customer 
engagement. 

   Problem Being Addressed 

Retail businesses often face challenges in understanding customer preferences, optimizing 
product lines, and improving sales consistency throughout the year. This project uses Excel to 
translate sales data into strategic insights that help improve product targeting, logistics 
efficiency, and marketing decisions. 

   Key Dataset and Methodologies 

The dataset includes detailed records of sales transactions across product categories, delivery 
platforms, states, and customer demographics. 

All analysis was conducted using Microsoft Excel, leveraging: 

• PivotTables for category and demographic segmentation 

• IF and COUNTIFS formulas for conditional insights 

• Charts and dashboards for visual storytelling 

• Slicers for interactivity and comparison of multiple dimensions 

**2. Story of Data**

The dataset tells the story of Vrinda Clothing Store’s retail journey in 2022, capturing sales 
across India. It includes order data, gender-based performance, product preferences, and the top
performing regions. 

   Stakeholders of the Project 

• Store managers seeking to optimize inventory and sales distribution 

• Marketing and product teams aiming to identify customer preferences 

• Business analysts tracking revenue trends and delivery performance 
Value to the Industry 

This analysis shows how Excel-based retail dashboards can convert raw transactional data into 
clear visual insights, supporting operational and strategic decision-making for fashion retailers. 

   Data Source 

The data was downloaded from kagglge.com

   Data Structure 

Each record represents an order with attributes such as: 

• Month (Jan–Dec) 

• Gender (Male/Female) 

• Product Category (Set, Kurta, Saree, Western Dress, etc.) 

• Delivery Channel (Amazon, Myntra, Flipkart, etc.) 

• Order Status (Delivered, Returned, Cancelled, Refunded) 

• Sales Amount (in INR) 

• Customer Age Group (Teenager, Adult, Senior) 

   Important Features and Their Significance 

• Sales Amount: Measures revenue performance. 

• Gender: Indicates customer purchasing trends. 

• Product Category: Identifies best-selling and underperforming product lines. 

• Delivery Channel: Evaluates platform efficiency and reach. 

• Order Status: Highlights operational effectiveness and fulfillment success rates. 

   Data Limitations 

Data represents one financial year (2022), so long-term seasonality patterns may not be fully 
captured. 

**3. Data Splitting and Preprocessing** 
   
   Data Cleaning 

• Duplicate entries were removed using Excel’s Remove Duplicates tool. 

• Missing or inconsistent category and delivery names were standardized. 

• Currency values were formatted to INR. 

   Handling Missing Data 

Missing order statuses were labeled as Unknown; blank sales values were imputed using the 
average monthly sales. 

   Data Transformation 

• New columns introduced for Quarterly Sales, Gender Contribution %, and Category 
Rank by Sales. 

• Order volumes grouped by Month, State, and Delivery Channel. 

   Data Splitting 

The data was analyzed across four dimensions: 

1. Sales Over Time 

2. Gender Performance 

3. Product Category Breakdown 

4. Delivery and Regional Distribution 

   Industry Context 

This analysis fits into the retail analytics and consumer insights domain, helping businesses like 
Vrinda optimize their sales and logistics operations. 
   
   Stakeholders 

• Sales and marketing departments 

• Supply chain managers 

• Retail strategy teams 

**4. Pre-Analysis Insights** 

• Monthly sales peaked in March, reaching ₹1.92M, before showing a steady decline 
toward December. 

• Women contributed significantly higher sales (₹13.56M) compared to men (₹7.61M). 

• Delivered orders accounted for over 92% of all transactions, indicating strong fulfillment 
performance. 

• Amazon led as the most popular delivery channel, followed by Myntra and Flipkart. 

• Maharashtra, Telangana, and Uttar Pradesh ranked among the top three shipping states by 
total sales. 

• Adults dominated the customer base, followed by teenagers and seniors. 

• Set and Kurta emerged as the top-selling product categories. 

• Bottoms and Blouses had the lowest revenue contributions, signaling potential for 
optimization or repositioning. 

• The consistent male-female purchasing gap suggests gender-specific marketing could 
boost sales among men. 

**5. In-Analysis Observations** 

• Women buyers consistently generated higher sales across all product types, especially in 
Sets and Kurtas. 

• Adults were the dominant age group driving the largest revenue share, with teenagers 
following closely in product diversity. 

• Sales trend reveals a sharp mid-year decline, possibly due to post-festival demand drops 
or seasonal slowdowns. 

• Product performance shows Sets contributed over ₹10.5M by far the best performed 
while Bottoms contributed less than ₹30K. 

• Regional analysis identified Maharashtra as the leading state in total shipment value. 

• Amazon alone handled over one-third of all orders, demonstrating strong platform 
reliability. 

• Return and cancellation rates remained low (below 8%), highlighting high customer 
satisfaction. 

• Ethnic wear categories like Sarees and Kurtas remain customer favorites, especially 
among adult and senior demographics. 

• The presence of multiple channels (Myntra, Flipkart, Ajio, etc.) indicates strong 
omnichannel coverage. 

• Despite end-of-year declines, the overall 2022 performance demonstrates stable brand 
loyalty and solid order fulfillment efficiency. 

Excel Techniques Used: 

• PivotTables: For filtering sales by month, gender, and category. 

• COUNTIFS and AVERAGEIFS: For analyzing order statuses and delivery rates. 

• Conditional Formatting: For identifying top 10 performing states. 

• Charts and Dashboards: Used for trend analysis and storytelling. 

**6. Post-Analysis Recommendations** 

• Product Strategy: Increase focus on Sets and Kurtas, while rebranding or bundling 
Bottoms and Blouses to boost sales. 

• Marketing Focus: Launch gender-specific campaigns to encourage more male 
purchases, possibly via online exclusives. 

• Regional Expansion: Strengthen logistics and marketing in top-performing states while 
exploring underperforming regions. 

• Delivery Optimization: Maintain strong partnerships with Amazon and Myntra, but 
incentivize sales through smaller platforms like Nalli and Meesho. 

• Customer Segmentation: Tailor promotions by age group ethnic wear for adults and 
western styles for teenagers. 

• Seasonal Campaigning: Introduce mid-year offers to offset the sales drop seen after 
March. 

• Inventory Planning: Align stock levels with quarterly demand trends to reduce 
overstock and clearance issues. 

• Dashboard Improvement: Add profitability and discount tracking to enhance future 
decision-making. 

   Comparison with Initial Findings 

The final insights confirmed early assumptions about female dominance in purchases and sets 
leading product sales, but also uncovered hidden opportunities in underperforming categories. 

**7. Data Visualizations & Charts**

Key visuals included in the dashboard: 

• Line Chart: Monthly Sales Trend (Jan–Dec). 

• Pie Charts: Gender Contribution, Order Status, Delivery Channels. 

• Map Chart: Top 10 States by Sales. 

• Bar Charts: Age Group by Gender, Product Category by Amount, Category Preference 
by Age Group. 

Each chart is interactive and visually designed to provide quick insights for management 
reporting. 

**8. Conclusion** 

This project demonstrates how Excel can transform retail data into business intelligence. 
The analysis revealed strong gender-based purchasing trends, regional sales concentration, and 
product hierarchy within Vrinda Clothing’s portfolio. 
It underscores the importance of data visualization and structured reporting for operational and 
marketing decisions in retail. 
While more advanced tools (like Power BI or Tableau) could enhance interactivity, this Excel 
dashboard effectively bridges the gap between data and decision-making proving that even 
simple tools can drive meaningful insights when used strategically.

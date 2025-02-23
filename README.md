# Customer Behavior and Sales Forecasting: EDA and Automation in Retail
This synthetic dataset simulates a bustling retail environment, allowing you to explore retail sales and customer characteristics. Uncover complex patterns and insights through exploratory data analysis (EDA), enhance understanding of customer behavior, and integrate sales forecasting and automation to streamline and predict future trends. 

## Data Set Used  
This dataset was sourced from **Kaggle** – *Retail Sales Dataset*.  

## Tools Used  
- **Python**  
- **Power BI**  

## Data Overview  
The dataset contains the following fields:  

- **Transaction ID**: Unique identifier for each transaction.  
- **Date**: The date of each transaction.  
- **Customer ID**: Unique identifier for each customer.  
- **Gender**: Gender of the customer.  
- **Age**: Age of the customer.  
- **Product Category**: Category of the purchased product.  
- **Quantity**: Number of units purchased.  
- **Price per Unit**: Cost of a single unit.  
- **Total Amount**: Total cost of the transaction.  

## Key Performance Indicators (KPIs)  
1. **Sales Growth Rate**  
2. **Customer Lifetime Value (CLV)**  
3. **Product Performance Index**  
4. **Average Transaction Value (ATV)**  
5. **Seasonal Sales Index**  
6. **Customer Engagement Rate**  
7. **Inventory Turnover Ratio**  

## Key Metrics to Track  
- **Sales Trends**: Monthly/quarterly sales growth.  
- **Customer Retention**: Repeat purchase rate of loyalty program members.  
- **Average Transaction Value**: Changes in the average transaction value.  
- **Product Performance**: Sales growth for promoted products.  
- **Customer Segmentation**: Spending behavior of high-value customers.  
- **Predictive Analysis**: Future demand and sales trend forecasting.  

## Critical Questions  
1. **What are the overall sales trends over time?**  
   - Are sales increasing, decreasing, or seasonal? Helps identify patterns and predict future performance.  
2. **Who are the top customers, and what are their buying behaviors?**  
   - Understanding which customer segments spend the most can help focus marketing efforts.  
3. **Which products are the best and worst performers?**  
   - Identifies what to promote and what might need re-evaluation or discontinuation.  
4. **What is the average sales value per transaction?**  
   - Helps gauge how much customers typically spend and identify opportunities to increase basket size.  
5. **Are there any sales peaks or dips we should prepare for?**  
   - Identifying seasonal trends helps in inventory planning and marketing campaigns.  
6. **How can these insights improve business decisions?**  
   - Translates insights into actionable strategies for customer engagement, product offerings, and sales growth.  

## Data Cleaning  
- **No missing values**  
- **No duplicates**  
- **No inconsistencies**  
- **Data type correction**: The *Date* column was originally stored as an **object**, so it was converted to `datetime64`.  

## Descriptive Statistics  
Performed calculations to summarize the dataset:  
- **Mean**  
- **Median**  
- **Mode**  
- **Standard deviation**

![Screenshot 2025-02-23 160435](https://github.com/user-attachments/assets/281f8ac6-a75f-4979-81d1-e8c96666ce7b)
  

# Time Series Analysis: Seasonal Sales Trends and Customer Behavior  
![Screenshot 2025-02-23 160518](https://github.com/user-attachments/assets/ac705a7b-7d35-40a2-8767-9f9fc84c5445)

## Sales Trends Overview  
The chart above highlights peak sales periods in **May, October, and December**, indicating strong **seasonal trends and customer behavior patterns**.  

## Possible Reasons for High Sales  

### **May**  
- **Spring Shopping**: Increased demand for clothing, outdoor products, and home improvement items.  
- **Mother's Day**: Surge in sales for beauty products, jewelry, and gifts.  
- **Pre-Summer Sales**: Higher purchases of summer-related products like swimwear and travel gear.  

### **October**  
- **Holiday Preparation**: Customers begin shopping for Halloween, Thanksgiving, and Christmas.  
- **Back-to-School Sales**: Increased demand for school supplies, clothing, and electronics (varies by region).  
- **Festive Discounts**: Retailers attract early holiday shoppers with promotions.  

### **December**  
- **Holiday Shopping**: Peak season for Christmas and New Year sales.  
- **Year-End Sales**: Clearance sales drive revenue and attract bargain hunters.  
- **Gift Purchases**: High sales across multiple categories due to holiday gifting.  

## Customer Behavior Insights  
The increased sales during these months indicate that purchasing behavior is influenced by external factors such as **holidays, seasons, and promotions**.  

### **Key Insights**  
- **Gift-Giving Culture**: Customers spend more during festive seasons (e.g., Mother's Day, Halloween, Christmas).  
- **Seasonal Needs**: Demand for seasonal products rises (e.g., winter clothing in December, summer items in May).  
- **Promotional Sensitivity**: Customers respond well to discounts and limited-time offers.  

## Business Opportunities  
To leverage these seasonal trends, businesses can implement the following strategies:  

- **Inventory Planning**: Stock up on high-demand products before peak months.  
- **Marketing Campaigns**: Run targeted promotions to capitalize on increased spending.  
- **Loyalty Programs**: Offer discounts or rewards to encourage repeat purchases.  
- **Upselling and Cross-Selling**: Bundle complementary products to increase average order value.  

## Recommendations  

### **For May**  
✅ Promote **Mother's Day gift bundles** (e.g., beauty products, jewelry, clothing).  
✅ Highlight **spring and summer collections** (e.g., outdoor gear, swimwear).  
✅ Run **pre-summer sales** to attract early shoppers.  

### **For October**  
✅ Launch **holiday-themed promotions** (e.g., Halloween costumes, decorations).  
✅ Offer **early-bird discounts** for Christmas shoppers.  
✅ Advertise **back-to-school essentials**, if applicable.  

### **For December**  
✅ Focus on **holiday gift guides** and curated gift sets.  
✅ Run **year-end clearance sales** to move inventory.  
✅ Offer **free shipping or expedited delivery** for last-minute shoppers.  


# **Product Category Analysis During Peak Sales Months**  

![Screenshot 2025-02-23 162417](https://github.com/user-attachments/assets/99fec351-5dbb-4dd6-bf00-3e1efcaa3931)

## **Top-Selling Categories**  
Based on the output, the product categories with the highest sales during peak months (**May, October, and December**) are:  

- **Electronics**: Total sales = **61,375**  
- **Clothing**: Total sales = **42,840**  
- **Beauty**: Total sales = **40,205**  

## **Interpretation of Results**  

### **Electronics**  
✅ **Top-performing category** during peak months.  
✅ Driven by **holiday gift purchases** (e.g., smartphones, laptops, gaming consoles).  
✅ Customers may upgrade devices or take advantage of year-end discounts.  

### **Clothing**  
✅ Sales align with **seasonal trends** (e.g., winter clothing in December, summer wear in May).  
✅ Boosted by **holiday shopping** and festive outfit demand.  
✅ Promotions and discounts increase sales volume.  

### **Beauty**  
✅ High demand due to **gift-giving occasions** (e.g., Mother's Day, Christmas).  
✅ Self-care trends during holidays drive increased purchases.  
✅ Customers stock up on beauty products during sales events.  

## **Actionable Insights**  

### **Electronics**  
- 🔹 **Promote High-Demand Items**: Focus on **smartphones, laptops, and gaming consoles**.  
- 🔹 **Bundle Offers**: Create **gift bundles** (e.g., smartphone + accessories) to increase average transaction value.  
- 🔹 **Early Bird Discounts**: Offer holiday discounts in **October** to capture early demand.  

### **Clothing**  
- 🔹 **Seasonal Collections**: Highlight **winter wear (December)** and **summer fashion (May)**.  
- 🔹 **Gift Guides**: Curate **holiday shopping guides** (e.g., "Top 10 Gifts for Her/Him").  
- 🔹 **Loyalty Programs**: Reward repeat customers with **exclusive discounts** or early access.  

### **Beauty**  
- 🔹 **Gift Sets**: Create **beauty bundles** (e.g., skincare or makeup kits) for holiday shoppers.  
- 🔹 **Promotions**: Run **"Buy 1, Get 1 Free"** or **discounts on premium beauty products**.  
- 🔹 **Personalization**: Offer personalized **product recommendations** based on customer preferences.  

# Customer Segmentation: Top Customers and Their Buying Behavior

## Sales Data Analysis

### Top Customers by Spending and Product Preferences

| Image | Description |
|-------|------------|
| ![Product Preferences](https://raw.githubusercontent.com/your-repo-path/Screenshot-2025-02-23-163803.png) | Product Preferences of Top Customers by Gender |
| ![Top Customers](https://raw.githubusercontent.com/your-repo-path/Screenshot-2025-02-23-164117.png) | Top 10 Customers by Spending |
| ![Sales by Customer Segment](https://raw.githubusercontent.com/your-repo-path/Screenshot-2025-02-23-163938.png) | Sales by Customer Segment and Product Category (Peak Months) |
| ![Sales Table](https://raw.githubusercontent.com/your-repo-path/Screenshot-2025-02-23-164141.png) | Sales Breakdown by Gender and Product Category |

### Key Insights:
- **Electronics**: Highest sales, especially among male customers.
- **Clothing**: Popular among female customers.
- **Beauty Products**: Balanced demand from both genders.
- **Top Customers**: Each spent 2000 during peak months.


---


---

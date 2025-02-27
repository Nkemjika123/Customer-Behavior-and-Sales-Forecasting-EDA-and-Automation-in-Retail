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

# Actionable Recommendations

##  Targeted Marketing Campaigns

### For Men (Electronics)
- Run tech-focused campaigns highlighting the latest gadgets and electronics.
- Use male-oriented channels (e.g., tech blogs, YouTube, social media ads targeting men).
- Offer bundles (e.g., smartphone + headphones) to increase the average transaction value.

### For Women (Clothing and Beauty)
- Run fashion and beauty campaigns showcasing seasonal collections and beauty trends.
- Use female-oriented channels (e.g., Instagram, Pinterest, beauty blogs).
- Promote gift sets (e.g., skincare kits, makeup bundles) for holidays and special occasions.

---

##  Personalized Recommendations

### For Men
- Recommend electronics based on purchase history (e.g., gaming consoles for gamers, laptops for professionals).
- Highlight tech accessories (e.g., smartwatches, headphones) as complementary products.

### For Women
- Recommend clothing based on style preferences (e.g., casual, formal, seasonal).
- Suggest beauty products based on skincare or makeup preferences (e.g., anti-aging creams, lipsticks).

---

##  Loyalty Programs

### For Men
- Offer tech-focused rewards (e.g., discounts on electronics, free accessories with purchases).
- Provide early access to new product launches or exclusive deals.

### For Women
- Offer fashion and beauty rewards (e.g., discounts on clothing, free beauty samples).
- Provide VIP perks (e.g., free styling sessions, makeup tutorials).

---

## 🛍 Seasonal Promotions

### For Men
- Run holiday promotions for electronics (e.g., "Black Friday Tech Deals").
- Offer gift guides for men (e.g., "Top 10 Gifts for Him").

### For Women
- Run seasonal fashion sales (e.g., "Summer Wardrobe Refresh").
- Offer beauty bundles for holidays (e.g., "Christmas Beauty Box").

---

##  Inventory Planning

### For Men
- Stock up on high-demand electronics (e.g., gaming consoles, smartphones) during peak months.
- Ensure availability of tech accessories (e.g., chargers, cases) to complement main purchases.

### For Women
- Stock up on seasonal clothing (e.g., winter coats in December, summer dresses in May).
- Ensure availability of popular beauty products (e.g., skincare sets, makeup palettes).

![Screenshot 2025-02-23 170247](https://github.com/user-attachments/assets/bb7f181f-6aa2-4d48-aa07-c8cf67c8ea36)

# Actionable Recommendations

## Electronics

### Focus on High-Demand Items
- Stock up on popular electronics (e.g., smartphones, laptops, gaming consoles).
- Highlight new product launches and limited-edition items.

### Bundle Offers
- Create bundles (e.g., smartphone + headphones, laptop + mouse) to increase the average transaction value.

### Targeted Marketing
- Run tech-focused campaigns on platforms like YouTube, tech blogs, and social media.
- Use email marketing to notify customers about new arrivals and discounts.

### Loyalty Programs
- Offer exclusive discounts or early access to electronics for loyal customers.

## Clothing

### Seasonal Collections
- Highlight seasonal clothing (e.g., winter coats in December, summer dresses in May).
- Promote holiday-themed outfits (e.g., Halloween costumes, Christmas sweaters).

### Personalization
- Use customer data to recommend clothing based on past purchases and preferences.
- Offer styling tips or outfit ideas to inspire customers.

### Promotions
- Run flash sales or buy-one-get-one (BOGO) offers to drive sales.
- Offer free shipping or returns to reduce purchase friction.

## Beauty

### Gift Sets
- Create beauty gift sets (e.g., skincare kits, makeup bundles) for holidays and special occasions.
- Promote these sets as perfect gifts for loved ones.

### Subscription Services
- Introduce a subscription box for beauty products to encourage repeat purchases.

### Educational Content
- Share beauty tutorials and skincare tips on social media to engage customers.

### Promotions
- Offer discounts on premium beauty products or free samples with purchases.

## Cross-Category Strategies

### Cross-Selling and Upselling
- Recommend complementary products (e.g., suggest beauty products to customers buying clothing or electronics accessories to customers buying gadgets).
- Use product recommendations on your website or app to increase basket size.

### Loyalty Programs
- Reward customers for purchases across all categories (e.g., points for every dollar spent).
- Offer tiered rewards (e.g., higher discounts for higher spending levels).

### Seasonal Campaigns
- Run holiday-themed campaigns that promote all three categories (e.g., "Tech, Fashion, and Beauty for the Holidays").
- Create gift guides that include electronics, clothing, and beauty products.

# Understanding Average Transaction Value (ATV)

![Screenshot 2025-02-23 181245](https://github.com/user-attachments/assets/7edbb970-1c7a-476e-9889-a4a3a2b20247)


An **Average Transaction Value (ATV)** of **$456.00** provides valuable insight into customer spending behavior. This metric represents the average amount customers spend per transaction. 

---

##  What Does an ATV of $456 Mean?

### 📈 High-Value Transactions  
- Customers are making significant purchases, contributing positively to revenue.  
- Indicates purchases of high-ticket items (e.g., **electronics**) or multiple items in one transaction.  

###  Customer Behavior  
- Customers may be responding well to **bundles, upselling, or cross-selling** strategies.  
- Promotions and discounts could be encouraging larger purchases.  

###  Revenue Potential  
- A high ATV suggests **effective revenue maximization** per customer.  
- Opportunities may still exist to **further increase ATV** with targeted strategies.  

---

##  How to Leverage This Insight

###  Upselling and Cross-Selling  
#### **Upselling**  
Encourage customers to **purchase higher-value products** (e.g., a premium smartphone instead of a basic model).  

#### **Cross-Selling**  
Recommend complementary products (**e.g., headphones with a smartphone, skincare with makeup**).  

 **Example:**  
- If a customer buys a **laptop**, suggest adding a **laptop bag, mouse, or extended warranty**.  

---

###  Bundle Offers  
- Create **discounted product bundles** to increase ATV while offering customer value.  

 **Example:**  
- **Tech Starter Kit:** Smartphone + headphones + case  
- **Beauty Essentials:** Skincare set + makeup palette  

---

###  Loyalty Programs  
Encourage customers to spend more by rewarding **higher transaction values**.  

 **Example:**  
- **Bronze:** 5% discount for spending **$300**  
- **Silver:** 10% discount for spending **$600**  
- **Gold:** 15% discount for spending **$1,000**  

---

###  Free Shipping Thresholds  
- Set a **free shipping** threshold just **above the current ATV** (e.g., “Free shipping on orders over **$500**”).  
- Encourages customers to **add more items to their cart**.  

---

###  Personalized Recommendations  
- Use **customer purchase data** to suggest relevant products.  
- **Personalized recommendations** increase the likelihood of larger transactions.  

 **Example:**  
- If a customer frequently buys **beauty products**, recommend **premium skincare sets** or **limited-edition makeup**.  

---

###  Limited-Time Offers  
- Create **urgency** with **flash sales and time-sensitive discounts**.  

 **Example:**  
- “**24-hour Flash Sale:** Get **20% off** all electronics today only!”  

#  Sales Trends and Insights

![Screenshot 2025-02-24 142311](https://github.com/user-attachments/assets/8882ba05-f0f8-4015-bb7d-9166cf5f3eec)

Analyzing sales patterns reveals **dips in March, June, September, and November** and **peaks in May, October, and December**. Understanding these trends can help optimize sales strategies.

---

##  Key Insights

### 📈 Sales Peaks (May, October, December)
- **May:** Driven by **Mother’s Day**, **spring shopping**, and **pre-summer sales**.  
- **October:** Marks the start of the **holiday shopping season** (Halloween, early Christmas shopping).  
- **December:** **Peak holiday season** with **Christmas & New Year shopping** boosting gift purchases.  

### 📉 Sales Dips (March, June, September, November)
- **March:** A slower month following holiday spending and before spring shopping picks up.  
- **June:** A transition period with fewer major shopping events.  
- **September:** A quiet month before the holiday shopping season begins.  
- **November:** Possible dip as customers **wait for Black Friday and Cyber Monday**.  


##  Actionable Recommendations

###  For Sales Peaks (May, October, December) - **Maximize Revenue**
✅ **Stock Up:** Ensure availability of high-demand items (**electronics, clothing, beauty**).  
✅ **Run Promotions:** Offer discounts, bundles, and limited-time deals.  
✅ **Targeted Marketing:**  
   - Launch **holiday-themed campaigns** (e.g., **"Mother’s Day Gift Guide"**, **"Christmas Countdown Deals"**).  
   - Use **email marketing & social media** to boost seasonal sales.  
✅ **Enhance Customer Experience:**  
   - Offer **fast shipping** and **hassle-free returns**.  
   - Provide **gift-wrapping services** for holiday shoppers.  

---

###  For Sales Dips (March, June, September, November) - **Boost Sales**
✅ **Run Off-Season Promotions:**  
   - **"Spring Clearance Sale"** in March.  
   - **"Back-to-School Sale"** in September.  
✅ **Flash Sales & Exclusive Discounts:** Encourage purchases during slower months.  
✅ **Inventory Management:**  
   - Use dips to **clear out excess stock**.  
   - Introduce **new or limited-edition products**.  
✅ **Customer Engagement Strategies:**  
   - Launch **loyalty programs** or reward points to increase retention.  
   - Gather customer feedback through **surveys & personalized offers**.  

---

##  Summary

By aligning your **inventory, marketing, and customer engagement** strategies with these **sales trends**, you can **increase revenue during peaks** and **minimize dips in slow months**.

 

 


---


---

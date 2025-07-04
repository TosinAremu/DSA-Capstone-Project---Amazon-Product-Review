# DSA Capstone Project - Amazon Product Review

## Project Title: Amazon Product Review Analysis

### Introduction
In the rapidly expanding e-commerce landscape, providing insightful product and customer data analysis is vital for enhancing customer satisfaction, optimizing marketing strategies, and driving product improvements. As a Junior Data Analyst at RetailTech Insights, our goal is to leverage the rich dataset obtained from Amazon product pages, which encompasses detailed product information and customer reviews across various categories. This analysis aims to uncover patterns, sentiments, and key factors influencing customer perceptions and product performance, thereby enabling e-commerce sellers to make data-driven decisions to boost their competitive edge.

### Project Summary
This portfolio presents insights derived from analyzing Amazon products from various categories. The focus is on identifying patterns in customer behaviour, product performance, pricing competitiveness, and sentiment in user feedback. The analysis combines both quantitative and qualitative methods to generate a comprehensive picture of each product's market performance.

### Data Sources
The dataset includes structured product and unstructured customer review data for products across multiple categories, with attributes such as:
- Product Information: ID, name, category, pricing, discount.
- Review Data: Ratings, review count, individual reviews (title + content).
- Customer Metadata: User ID, name.

### Data Cleaning & Preprocessing Highlights
- Standardized Column columns: Unified naming conventions and trimmed product category.
- Calculated Column: Calculated derived field like, average discount percentage, number of products, review per category, average actual and discounted prices etc.
- Price columns: Converted to numeric and calculated derived fields like revenue = actual_price x rating count.

### Tools & Techniques Used:
Excel Sheet - Initial data exploration, clean up and structuring and re-organising. [Download Here](https://mpel-my.sharepoint.com/:x:/g/personal/tosin_mpel_co_uk/ETybyULWLtRBiA6ubTGXj-YBNup_W7WNP1UsL7IxeMplsA?e=jaXbmS)

### Analysis & Insights
The functions used for the analysis are:
1. UNIQUE
2. AVERAGEIF
3. COUNTIFS
4. SUMIFS
5. MAXIFS
6. FREQUENCY
7. RANK
8. IF
9. IFERROR

![Excel Dashboard](https://github.com/user-attachments/assets/be923a3d-a0cd-421f-99c5-571beac0e88c)

#### Overview of the Dashboard
This dashboard provides a summarized view of sales performance and customer reviews across different categories on Amazon with a focus on;
- Revenue Performance
- Category distribution
- Number of products
- Average rating
- Top 10 revenue generating products

#### Key Metrics

|Metric|Value (#)|Insight
|------|---------|------|
|Revenue|4,472,000|This is the revenue generated from the selected category "Car&Motorbike"
|Product Categories|9|There are a total of 9 distinct product categories in the dataset.
|Products|71|There are 71 products in the selected category.
|Average Rating|292.75|This is the average number of ratings/reviews received.

#### Revenue by Categories (Bar Graph)
This bar chart breaks down revenue per category.
|Category|Revenue #(Million)|Observations
|--------|-----------------|-----------|
|Electronics|98,020.81|Highest revenue contributor by a wide margin.
|Computers & Accessories|12,614.81|2nd Highest contributors. Likely includes laptops, peripherals.
|Health & Personal Care|10,459.72|High value from daily essentials or wellness electronics.
|Home & Kitchen|6.96|Surprisingly low despite being a common shopping category.
|Car & Motorbike|4.47|Contributing very little.
|Home Improvements|6.16|Modest contribution.
|Musical Instruments|151.12|Niche category with above average performance.
|Office Products|60.78|Low revenue generation.
|Toys & Games|2.38|One of the least perfoming categories.

#### Insights:
- Electronics dominates the revenue with #98 billion.
- Disproportionate revenue gap between electronics and other categories suggests a high dependency on this category.

#### Top 10 Products by Revenue
1. Smartphones & Basic Mobiles - Massive lead, core of Amazon Electronics sales.
2. Televisions - Strong performer in the consumer electronis segments.
3. SmartwWatches - High sales volume wearble tech.
4. Headphones - Suggests strong demand for personal audio.
5. Small Kitch Appliances - Leading Home7Kitchen sub category.
6. Cables & Accessories - Utility items like chargers, USBs, HDMI.
7. Memory Cards - Likely declining as cloud storage grows.
8. Mobile Accessories - Phone cases, stands, etc.
9. Accessories - General or wearable accessories.
10. Cleaning - Home appliances segment.

#### Insights:
- The top 4 products are all electronics-related, underscoring Amazon's dominace in the tech market.
- Products like "vacuum cleaners" and "kitchen appliances" show potential in home related segments.
- There is a drop in revenue after top 5 products.

#### Key Takeaways
1. Electronics is king, commanding an overwhelming majority of total revenue.
2. Car & Motorbike has low revenue and limited product count, suggesting it's a niche or underdeveloped segmenet.
3. Highly rated products (avg. rating of 292.75) in Car & Motorbike imply strong user engagement per product, even if revenue is low.
4. Product deiversity is broad, but contributions are unequal with a few categories (Electronics, Computers) driving most of the business.
5. Top selling products are tech centric, hinting at consumer preference on Amazon.

### Sentiment Analysis (Selected Snippets)
|Product|Positive Sentiment|Negative Sentiment
|-------|------------------|-----------------|
|Wayona Nylon Braided USB|"Charging is really fast". "Looks durable".|Minor complaints about needing replacement.
|Fire-Boltt Watch|“Perfect for beginners”. “Premium strap”.|Screen doesn’t turn on with tap.
|HDMI Cable|“Value for money”. “Just go for it”.|Few mentions about cable length.
|Camel Paints|“Colour texture is great”.|Rare quality concerns.
|Pens|“Excellent performance”.|Received only 20 pens out of 25.
|Lenovo Charger|“Original and fast charging”.|None significant.

### Overall Market Insights
- High Customer Ratings & Engagement: Most products boast ratings above 4 stars with thousands of reviews, indicating high customer satisfaction and trust.
- Discount-Driven Sales: Significant discounts (often exceeding 50%) are common, suggesting a competitive pricing strategy to drive volume.
- Consumer Priorities: Durability, compatibility, and value for money are recurring themes across categories.
- Potential Areas for Improvement: Some products reveal minor issues like build quality (monitors), battery life (smartwatches), or missing product components (pens),highlighting opportunities for quality enhancement and clearer product descriptions.

### Strategic Recommendations
1. Leverage High-Rated Products: Promote products with high review counts and ratings as trusted options.
2. Highlight Discount Offers: Emphasize significant discounts to attract price-sensitive customers.
3. Address Customer Feedback: Improve product features based on common complaints, such as adding audio ports to monitors or increasing battery life in smartwatches.
4. Expand Compatibility & Features: For tech products, expanding compatibility and incorporating popular features can increase appeal.

### Summary
The dataset reveals a vibrant market with strong customer preferences for durable, feature-rich, and cost-effective products. Brands that focus on quality assurance, clear communication, and competitive pricing are likely to sustain high customer loyalty and market share.








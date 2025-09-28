# 📊 Marketing Performance & Customer Insights Analysis

## Project Overview

This data analysis project focuses on optimizing marketing performance across three critical areas: **Conversion, Engagement, and Customer Satisfaction**. The goal is to transform raw data into actionable business recommendations to drive revenue growth and build stronger customer relationships.

The analysis is conducted using Python for data extraction and transformation, and visualized via a comprehensive Power BI Dashboard.
![1](https://github.com/user-attachments/assets/2eb5917a-c2de-45c1-8b0a-54426bb332cb)![2](https://github.com/user-attachments/assets/956c0f83-38e7-4f0e-a130-8d5c49b96413)
![3](https://github.com/user-attachments/assets/15efb03a-fd22-495d-be8a-6d0ddc889611)
![4](https://github.com/user-attachments/assets/ce4db26b-d32f-4f75-9299-c99549086ae5)


## 🎯 Project Goals and Business Questions

The project is structured around three core business objectives:

| Goal | Description | Key Insight Delivered |
| :--- | :--- | :--- |
| **Increase Conversion Rates** | Identify factors that significantly impact the purchase funnel and conversion performance. | Highlight key drop-off stages in the funnel and provide targeted recommendations for optimization. |
| **Enhance Customer Engagement** | Determine which types of marketing content (e.g., Blog, Social Media, Video) drive the highest user interaction. | Analyze Views, Clicks, and Likes across content types to inform future content strategy and budget allocation. |
| **Improve Customer Feedback Scores** | Understand common themes, sentiments, and pain points expressed in customer reviews. | Identify recurring positive/negative feedback associated with specific products or services to guide quality and service improvements. |

## 🛠️ Data & Methodology

### Step 1: Data Source & Extraction

The data for this analysis is stored in a database environment. The initial step involved connecting to the database and extracting the necessary tables using SQL, which were then loaded into a data analysis environment (e.g., Python/Pandas).

The key tables extracted included:

| Table Name (Example) | Description | Primary Use Case |
| :--- | :--- | :--- |
| `Conversion_Funnel` | Records of customer steps (View, Click, Purchase) and their associated product/campaign. | Conversion Rate Analysis |
| `Content_Interactions` | Logs of views, likes, and comments for marketing content, segmented by type (Blog, Social, Video). | Customer Engagement Analysis |
| `Customer_Reviews` | Customer-submitted reviews, rating scores, and extracted sentiment (Positive, Negative, Neutral, Mixed). | Customer Feedback Analysis |

### Step 2: Data Transformation and Cleaning (ETL)

All data underwent rigorous cleaning and transformation processes in Python:

* **Data Type Handling:** Ensured correct formatting for dates, numerical rates, and categorical identifiers.
* **Funnel Calculation:** Calculated conversion rates for each stage (`Click/View`, `Purchase/Click`).
* **Sentiment Categorization:** Standardized sentiment scores and review text for thematic analysis.
* **Feature Engineering:** Created time-based features (e.g., `Month`, `Year`) for trend analysis.

### Step 3: Analysis and Dashboard Development

The clean data was modeled and visualized in **Power BI** to create an interactive dashboard, allowing business stakeholders to explore insights across product lines, time periods, and customer segments.

## 🖼️ Key Dashboard Pages (Visual Evidence)

The final dashboard is structured into three main pages, directly addressing the project goals:

### 1. Conversion Analysis Details

This page tracks the funnel from **View** to **Purchase** and shows conversion rates segmented by product and month, enabling identification of conversion bottlenecks.

### 2. Social Media Details (Engagement)

This page analyzes the performance of marketing content, displaying total **Views, Clicks, and Likes**, segmented by content type and time.

### 3. Customer Review Details (Feedback)

This page provides an overview of customer satisfaction, showing the **Average Rating**, distribution of **Sentiment Categories**, and a direct list of reviews for detailed exploration.

## 🚀 Key Recommendations (Insights to Action)

### Insight 1: Conversion Improvement

* **Problem:** The largest drop-off in the funnel occurs between the **Click** and **Purchase** stages (e.g., only **5.7%** conversion from click-to-purchase shown in the `2024` data).
* **Recommendation:** Focus resources on optimizing the product page (e.g., clear CTAs, improving loading speed, addressing cart abandonment) to improve the Click-to-Purchase rate, which is the most expensive bottleneck.

### Insight 2: High-Performing Content

* **Observation:** Content categorized as **"Video"** drives the highest engagement rates (clicks and likes relative to views) in comparison to Blog or Social Media content.
* **Recommendation:** Increase investment in high-quality video content production and distribution, particularly around top-converting product categories like **Kayak** and **Ski Boots**.

### Insight 3: Customer Feedback Themes

* **Observation:** A high volume of **Negative** reviews for "Ski Boots" mentioned **"fit and sizing issues,"** while **Positive** reviews frequently praised **"customer support speed"**.
* **Recommendation:** Launch a product-specific campaign to revise the sizing guide for Ski Boots immediately, and leverage the strength of fast customer support in marketing materials.



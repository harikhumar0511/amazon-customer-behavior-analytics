# Amazon Customer Behavior & Experience Analytics

## Project Overview
This project presents an end-to-end analysis of Amazon’s marketplace by combining product data, customer behavior patterns, and review sentiment into a structured data story. The analysis answers three core questions: what customers buy, how they shop, and how they feel after purchasing.

The project is delivered as an interactive, multi-page website that walks through the analysis using a narrative storytelling approach supported by data visualizations and NLP-based sentiment insights.

---

## Project Structure (Data Storytelling Approach)
The analysis is organized into three acts, mirroring how a product or business leader would reason through the problem.

### Act I – What Products Are Sold
- Category-level product distribution and sales concentration
- Price vs. quality analysis (rating vs. price paradox)
- Discounting strategies across categories
- Review engagement patterns by category

### Act II – Understanding Customer Engagement Patterns
- Customer segmentation by purchase recency
- Seasonal and event-driven behavior shifts (Prime Day, holidays)
- Category-level repeat purchase and retention patterns
- Behavioral signals distinguishing loyal vs. occasional customers
- Demographic breakdowns across age, gender, and category

### Act III – Inside the Customer Experience
- Review volume trends over time
- Sentiment distribution across categories
- Text sentiment vs. star-rating mismatch analysis
- Emotion extraction from customer reviews
- Identification of top drivers of negative feedback

The final section synthesizes insights into actionable recommendations and estimated revenue impact.

---

## Data Sources
This project uses publicly available Amazon datasets curated by Julian McAuley (UC San Diego).

Primary source:
https://nijianmo.github.io/amazon/index.html

Datasets used include:
- Amazon Product Metadata
- Amazon Customer Reviews (ratings and review text)

Data handling note:
The original datasets contain hundreds of thousands of products and tens of millions of purchase and review records. Due to dataset size and licensing constraints, raw data is not included in this repository. The data folder contains sampled and anonymized CSV files that preserve the original schema and analytical logic.

---

## Analytical Methods
- Exploratory Data Analysis (EDA) on product, price, and category metrics
- Customer segmentation using recency-based behavioral grouping
- NLP-based sentiment analysis on review text
- Emotion analysis to capture underlying customer reactions
- Behavioral pattern analysis across browsing, purchasing, and reviewing activity
- Scenario-based estimation of potential revenue impact

---

## Tools and Technologies
- Python (Pandas, NumPy)
- NLP for sentiment and emotion analysis
- Data visualization using Flourish and Datawrapper
- Jupyter Notebooks for analysis
- Web presentation using HTML, CSS, JavaScript, and embedded React components

---

## Repository Structure
amazon-customer-behavior-analytics/

├── data/ # Sampled and anonymized datasets

├── notebooks/ # EDA, segmentation, and sentiment analysis

├── website/ # Interactive multi-page data story

└── README.md

## Key Insights and Business Takeaways
- Product volume does not directly translate to sales efficiency; mid-priced products consistently outperform premium-priced products in customer satisfaction
- Beauty and Personal Care shows the strongest repeat purchase behavior and emotional engagement
- Electronics and Home categories generate the highest review volume but also concentrate negative sentiment
- Star ratings alone often mask dissatisfaction; review text provides earlier and more accurate signals of customer issues
- Addressing the top drivers of negative feedback (product quality, delivery reliability, information clarity) can unlock double-digit revenue growth without adding new products

## Interactive Website
This project is presented as a live, interactive website with narrative explanations and dynamic visualizations.


## Why This Project Stands Out
- End-to-end ownership from raw data to business recommendations
- Strong focus on customer experience and decision-making
- Combines behavioral analytics with NLP-based sentiment and emotion analysis
- Delivered as an executive-friendly, interactive data product

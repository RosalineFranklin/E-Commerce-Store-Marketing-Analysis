Overview:
 - Full-stack portfolio project analyzing customer sentiment and purchasing behavior.
 - Combined SQL, Python (NLP), and dashboards to derive insights and drive business recommendations.

Objectives:
 - Analyze customer sentiment using text reviews and ratings.
 - Cross-reference NLP sentiment scores with star ratings to detect mismatches.
 - Segment feedback into actionable categories.
 - Deliver dashboards and executive summaries to stakeholders.

Tools & Technologies:
 - SQL Server (Microsoft SQL Server): data extraction from customer_reviews table.
 - Python (Pandas, NLTK, VADER): sentiment analysis and feature engineering.
 - Power BI & Excel: dashboard visuals and reporting.
 - pyodbc: SQL connection to Python.
 - SPSS & Qualtrics: survey/statistical support (from prior research experience).

Project Components:
 - Queried SQL database for review and rating data.
 - Used VADER (from NLTK) to calculate compound sentiment scores.
 - Engineered new columns: SentimentScore, SentimentCategory, SentimentBucket.
 - Output enriched review dataset: fact_customer_reviews_with_sentiment.csv.

Deliverables:
 - Python script for sentiment scoring.
 - Power BI & Excel dashboards showing sentiment trends by product and review mix.
 - PowerPoint: Market Analysis Presentation.pptx for stakeholders.
 - Full narrative: Shop Easy Market Analysis Report.docx.
 - Dashboard and data model screenshots.
 - SQL Query documentation for all ETL steps.

Key Insights:
 - Identified 12% of reviews where text sentiment contradicted star rating (valuable for QA).
 - Positive sentiment most strongly tied to delivery speed and service responsiveness.
 - Suggested product and marketing enhancements based on sentiment segmentation.

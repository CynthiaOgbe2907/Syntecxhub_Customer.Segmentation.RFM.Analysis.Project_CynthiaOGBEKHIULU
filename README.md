# Syntecxhub_Customer.Segmentation.RFM.Analysis.Project_CynthiaOGBEKHIULU

Dashboard Architecture & Views

​The interactive Power BI dashboard consists of a highly sophisticated 3-page reporting system supplemented by a dedicated business documentation matrix:

​1. Customer Demographics View
 ​
 
 High-Level KPIs: Instant visibility into Total Sales ($29.36M) and unique Customer Count (18.484K).
​Geographical Distribution: An interactive global map visual tracking sales weight across major territories including North America, Europe, and Australia.
​Socio-Demographic Profiling: Granular breakdown of sales by Gender, Marital Status, and distinct Age Bands (identifying the 55–64 demographic as the highest-performing bracket at $11.5M).

​2. Customer Segmentation (RFM Analysis) View
 
 Segment Volume & Revenue Contrast: Side-by-side analysis contrasting the number of customers in a segment against their total sales contribution (e.g., highlighting that while "New Customers" represent the largest volume, "Champions" and "Loyal" segments generate the overwhelming majority of revenue).
​RFM Metric Deep-Dive: Micro-distribution bars visualizing the precise Recency, Frequency, and Monetary performance distinct to each customer tier.

​3. Customer Details Matrix

​Granular Operational List: A fully filterable data grid providing granular details per customer—including Customer ID, Name, Email, Demographics, Total Lifetime Spend, and their precise assigned RFM Segment. This sheet allows marketing teams to export targeted lists instantly for localized campaigns.

​4. RFM Documentation & Action Plan
 
Strategic Playbook: Built straight into the reporting file, this framework outlines the explicit definitions for behaviors like "About To Sleep", "At Risk", and "Champions" alongside corresponding, data-driven marketing action items (e.g., automated win-back surveys, VIP previews, or targeted reactivation discounts).

​🛠️ Technical Stack & Concepts Used
​
BI Tool: Power BI Desktop
​Data Modeling: Star Schema design optimized for performance.
​Advanced DAX Formulas:
​Context transition utilizing CALCULATE and ALLEXCEPT for localized customer aggregates.
​Statistical distribution modeling leveraging PERCENTILE.INC variables to programmatically assign tiered scores (1–5) for Recency and Frequency.
​Conditional logic structures via SWITCH(TRUE(), ...) for clean segment mapping.

​🚀 Key Business Takeaways
 
 Retention Tool: Quickly isolate the 1.8K "At Risk" customers or high-value "Cannot Lose Them" personas to deploy immediate churn-prevention workflows.
​Personalization Engine: Equips growth teams to tailor bespoke email workflows based on authentic historical purchasing behaviors rather than intuition.

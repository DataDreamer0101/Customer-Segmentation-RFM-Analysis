# 🛍️ Customer Segmentation using RFM Analysis  

This project applies **RFM (Recency, Frequency, Monetary) Analysis** to the [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail).  
It is part of my **Elevvo Pathways Data Analytics Internship** and demonstrates **data cleaning, feature engineering, customer analytics, and visualization** in Python.  

---

## 📊 Project Workflow  

1. **Data Loading & Cleaning**  
   - Removed missing `CustomerID`s, cancellations, and negative values  
   - Created a new feature: `TotalPrice = Quantity * UnitPrice`  

2. **RFM Feature Engineering**  
   - **Recency**: Days since last purchase  
   - **Frequency**: Number of purchases  
   - **Monetary**: Total spending  

3. **Scoring & Segmentation**  
   - Assigned scores (1–5) for R, F, M  
   - Created combined **RFM Score**  
   - Grouped customers into segments:  
     - Champions  
     - Loyal Customers  
     - At Risk  
     - Recent Customers  
     - Big Spenders  
     - Frequent Buyers  
     - Others  

4. **Visualization**  
   - Segment Distribution (bar chart with labels)  
   - Heatmap of Avg. RFM by Segment  
   - Revenue Contribution by Segment  
   - Scatterplot (Recency vs Frequency)  

5. **Marketing Strategy Suggestions**  
   | Segment          | Strategy |
   |------------------|----------|
   | Champions        | Exclusive rewards, early access |
   | Loyal Customers  | Loyalty discounts, VIP offers |
   | At Risk          | Win-back campaigns |
   | Recent Customers | Welcome emails, onboarding |
   | Frequent Buyers  | Bundles & upselling |
   | Big Spenders     | Personalized offers, premium services |
   | Others           | Awareness campaigns |

---

##  Tools & Libraries  
- Python 
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

##  Key Outputs  
- ✅ Clean dataset ready for RFM analysis  
- ✅ RFM table with scores  
- ✅ Customer segments distribution  
- ✅ Heatmaps & bar charts  
- ✅ Actionable business insights  


## 📈 Results & Insights  
- Identified **Champions & Loyal Customers** as the highest value groups  
- Found **At Risk customers** needing re-engagement  
- Created segment-wise marketing strategies to boost retention and revenue  

---

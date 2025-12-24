# Customer Segmentation using K-Means Clustering (RFM Analysis)

## Overview
This project focuses on **customer segmentation for an online retail dataset** using the **RFM (Recency, Frequency, Monetary) model** and **K-Means clustering**.  
The goal is to identify distinct customer groups based on purchasing behavior and derive actionable business insights.

The methodology is inspired by the research paper:
> *Chen et al., “Data mining for the online retail industry: A case study of RFM model-based customer segmentation”, Journal of Database Marketing, 2012.*

---

## Dataset
- Online retail transactional data
- Each transaction includes invoice details, purchase quantity, price, invoice date, and customer identifier.
- Data is preprocessed to compute:
  - **Recency**: Time since last purchase
  - **Frequency**: Number of transactions
  - **Monetary**: Total spending per customer

---

## Methodology
1. **Data Cleaning & Preprocessing**
   - Removed invalid and missing records
   - Filtered relevant transactions
   - Aggregated transactional data at customer level

2. **Feature Engineering**
   - Computed RFM features for each customer
   - Applied feature scaling to handle differing magnitudes

3. **Clustering**
   - Applied **K-Means clustering**
   - Evaluated multiple values of *k*
   - Interpreted clusters based on RFM characteristics

4. **Visualization & Interpretation**
   - Visualized cluster distributions
   - Identified high-value, loyal, medium-value, and low-value customer segments

---

## Results & Insights
- Successfully segmented customers into distinct behavioral groups
- Identified a small segment contributing disproportionately high revenue
- Highlighted customer groups requiring retention or re-engagement strategies
- Demonstrated practical application of clustering for **customer-centric marketing**

---

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Reference
Chen, D., Sain, S. L., & Guo, K. (2012).  
*Data mining for the online retail industry: A case study of RFM model-based customer segmentation.*  
Journal of Database Marketing & Customer Strategy Management.

---

## Author
**Harshit Paramhans**

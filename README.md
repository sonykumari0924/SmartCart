# 📊 E-commerce Customer Segmentation System

## 📌 Overview

This project focuses on segmenting customers based on their behavior, demographics, and spending patterns using clustering techniques. The goal is to identify distinct customer groups and design targeted marketing strategies for each segment.

---

## 🎯 Objectives

* Understand customer behavior using data analysis
* Reduce dimensionality using PCA
* Apply clustering algorithms (K-Means, Hierarchical)
* Evaluate clusters using Silhouette Score & Elbow Method
* Derive actionable business insights

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Kneed (for elbow detection)

---

## 📂 Dataset Features

* **Income** – Customer income
* **Recency** – Days since last purchase
* **NumWebPurchases, NumStorePurchases, NumCatalogPurchases**
* **NumWebVisitsMonth**
* **Total_Spending**
* **Response, Complain**
* **Age, Customer_Tenure_Days**
* **Total_Children, Education, Living_With**

---

## ⚙️ Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Encoding & Scaling
4. PCA (Dimensionality Reduction)
5. Finding Optimal Clusters (Elbow + Silhouette)
6. Clustering (K-Means, Agglomerative)
7. Cluster Analysis & Interpretation

---

## 📈 Model Evaluation

* **Elbow Method (WCSS)** → Identify optimal K
* **Silhouette Score** → Measure cluster quality

---

## 👥 Customer Segments

### 🔴 Cluster 0: Family Shoppers

Low income, more children, high browsing but low purchases.
➡️ Strategy: Discounts & coupons

### 🔵 Cluster 1: Loyal High-Value Customers

High income, fewer children, high spending across channels.
➡️ Strategy: Loyalty programs & rewards

### 🟡 Cluster 2: Digital Browsers

Low income, mostly single, very high web visits but low spending.
➡️ Strategy: Heavy discounts & promotional offers

### 🟢 Cluster 3: High-Value Singles

High income, best response, strong purchasing behavior.
➡️ Strategy: Premium & personalized services

---

## 🧠 Key Insights

* Income strongly influences spending behavior
* Multi-channel customers spend more
* High web visits do not guarantee purchases
* Family size negatively impacts spending
* Premium customers generate highest ROI

---

## 📎 Conclusion

Customer segmentation helps businesses move from generic marketing to **data-driven personalized strategies**, improving both customer experience and ROI.

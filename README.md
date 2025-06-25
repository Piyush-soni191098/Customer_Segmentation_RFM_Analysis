# 🧠 Customer Segmentation using RFM Analysis

This project focuses on segmenting customers based on their purchasing behavior using **RFM Analysis** (Recency, Frequency, Monetary) to identify high-value customer groups and support targeted marketing strategies.

---

## 📌 Problem Statement

To analyze customer purchase history and segment customers into meaningful groups using RFM metrics in order to improve marketing campaigns, customer retention, and revenue generation.

---

## 📊 Dataset Overview

The dataset includes customer transaction history with features like:

- **Customer ID**
- **Invoice Date / Order Date**
- **Quantity**
- **Unit Price**
- **Total Purchase Value**

From this data, we calculated:

- **Recency**: Days since the customer's last purchase
- **Frequency**: Total number of purchases made
- **Monetary**: Total amount spent by the customer

---

## 🧹 Data Preprocessing

- Handled missing values and removed invalid transactions  
- Converted `date` columns to datetime format  
- Created new features: `TotalSpent`, `TotalOrders`, `LastPurchaseDate`  
- Engineered **RFM metrics** for each customer  
- Normalized features using **MinMaxScaler**

---

## 🧠 Techniques & Tools Used

- **Python (Pandas, NumPy, Matplotlib, Seaborn)**
- **Scikit-learn**: KMeans, Scaling, PCA
- **RFM Analysis** for feature engineering
- **Clustering Models**: KMeans Clustering
- **Visualization**: Pairplot, Elbow Plot, Cluster Scatter Plot

---

## 🤖 Algorithms Applied

- Applied **KMeans Clustering** to group customers based on RFM scores  
- Used **Elbow Method** to determine the optimal number of clusters  
- Visualized clusters using scatter plots and color-coded segment distribution

---

## 📈 Key Insights

- Segmented customers into distinct groups:  
  - 🎯 **High-value customers**
  - 🔁 **Frequent buyers**
  - 💤 **Inactive or at-risk customers**
  - 💸 **Low-spend occasional buyers**

- Most valuable customers had **high frequency and monetary value** with **recent purchases**

- The business can now design **targeted marketing campaigns** for each segment:
  - Loyalty programs
  - Retention offers
  - Re-engagement strategies

---

## 📊 Visualizations

- RFM Score Distribution  
- Elbow Plot (Optimal Clusters)  
- 2D & 3D Cluster Visualization  
- Customer Distribution by Segment  

> *(Add screenshots or link to visual outputs here if available)*

---


## 👥 Utility for Stakeholders

- Enables **data-driven marketing decisions**
- Helps in **retaining high-value customers**
- Allows **targeted promotions** and **budget optimization**
- Improves **customer satisfaction and lifetime value**

---

## 👤 Author

**Piyush Soni**  
Data Analyst | Customer Insights Enthusiast  
📧 sonipiyush8282@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/piyush-soni191098) | [GitHub](https://github.com/Piyush-soni191098)

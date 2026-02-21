# Customer Segmentation Using K-Means Clustering

## 📊 Project Overview

Understanding customer behavior is critical for businesses aiming to improve marketing effectiveness and increase revenue. This project applies **unsupervised machine learning (K-Means clustering)** to segment mall customers based on income and spending behavior.

The objective is to identify distinct customer groups and provide actionable business recommendations for targeted marketing strategies.

---

## 🎯 Business Problem

Retail businesses often treat all customers similarly, leading to inefficient marketing campaigns and missed revenue opportunities.

This project answers the question:

> Can we identify distinct customer segments based on income and spending patterns to enable targeted marketing strategies?

---

## 📁 Dataset Description

The dataset contains 200 mall customers with the following features:

| Feature                | Description                                       |
| ---------------------- | ------------------------------------------------- |
| CustomerID             | Unique customer identifier                        |
| Gender                 | Customer gender                                   |
| Age                    | Customer age                                      |
| Annual Income (k$)     | Annual income in thousand dollars                 |
| Spending Score (1–100) | Score assigned by mall based on spending behavior |

For clustering, we focused on:

* **Annual Income**
* **Spending Score**

These variables directly reflect purchasing power and behavior.

---

##  Methodology

### 1️⃣ Data Exploration

* Checked for missing values
* Reviewed summary statistics
* Visualized variable relationships

### 2️⃣ Feature Scaling

Since K-Means is distance-based, features were standardized to ensure fair clustering.

### 3️⃣ Model Selection

Two evaluation techniques were used:

* **Elbow Method**
* **Silhouette Score**

Both methods indicated that **5 clusters** provide the optimal segmentation.

### 4️⃣ Final Model

K-Means clustering with `k = 5` was used to segment customers.

---

## 📈 Customer Segments Identified

| Cluster | Segment Name       | Characteristics             |
| ------- | ------------------ | --------------------------- |
| 0       | Standard Customers | Moderate income & spending  |
| 1       | Premium Customers  | High income & high spending |
| 2       | Impulsive Spenders | Low income & high spending  |
| 3       | Careful Wealthy    | High income & low spending  |
| 4       | Budget Customers   | Low income & low spending   |

---

## 💡 Business Recommendations

### Premium Customers

* Loyalty programs
* VIP memberships
* Exclusive product launches

### Impulsive Spenders

* Flash sales
* Limited-time offers
* Promotional alerts

### Careful Wealthy Customers

* Personalized campaigns
* Premium product education
* Value-based messaging

### Budget Customers

* Discounts and bundles
* Price-based promotions

### Standard Customers

* Cross-selling strategies
* Seasonal promotions

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📌 Key Takeaways

* Customer behavior varies significantly even among similar income groups.
* Behavioral segmentation is more powerful than demographic grouping alone.
* Data-driven marketing can improve targeting and increase business revenue.

---

## 🚀 Future Improvements

* Include Age and Gender in clustering
* Compare with Hierarchical Clustering
* Deploy segmentation model as a web app
* Apply to larger real-world retail dataset

---

## 👤 Author

**FAYEMI ANTHONY**
Aspiring Data Analyst / Data Scientist
GitHub: [https://github.com/tonitokunbo](https://github.com/tonitokunbo)

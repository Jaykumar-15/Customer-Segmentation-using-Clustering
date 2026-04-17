# 🛒 Customer Segmentation using Clustering

## 📌 Project Overview

This project builds a **Customer Segmentation System** using **unsupervised machine learning** to group customers based on purchasing behavior, demographics, and engagement.

The goal is to help businesses:

* Identify high-value customers
* Improve targeted marketing
* Enhance customer retention strategies

---

## ⚠️ Problem Statement

SmartCart, an e-commerce platform, collects large amounts of customer data but currently applies **generic marketing strategies** to all users.

This leads to:

* Inefficient marketing campaigns
* Poor customer retention
* Lack of personalized engagement

To solve this, we build a **clustering-based segmentation system** that identifies distinct customer groups.

---

## 📊 Dataset Description

Each record represents a customer with features like:

* Demographics (Age, Income, Education)
* Purchase behavior (Spending on products)
* Engagement (Website visits, purchases)
* Recency (Last purchase activity)

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## 🔍 Workflow

* Data Cleaning & Preprocessing
* Feature Selection
* Scaling
* Elbow Method (optimal clusters)
* K-Means Clustering
* Visualization & Insights

---

## 📈 Results

### Dataset Preview

![Dataset](images/dataset.png)

### Data Summary

![Info](images/info.png)

### Preprocessing

![Preprocessing](images/preprocessing.png)

### Elbow Method

![Elbow](images/elbow.png)

### Customer Clusters

![Clusters](images/clusters.png)

---

## 🧠 Key Insights

* Customers grouped into distinct segments
* Identified high-spending and low-engagement users
* Enabled targeted marketing strategies

---

## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook
```

---

## 📌 Future Improvements

* Use DBSCAN / Hierarchical clustering
* Deploy as web dashboard
* Real-time customer segmentation

---

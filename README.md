# 🛍️ Customer Segmentation Using K-Means Clustering

This project applies the **K-Means clustering algorithm** to the **Mall\_Customers.xls** dataset to segment customers based on their purchasing behavior. The goal is to help businesses better understand customer groups for targeted marketing and personalized experiences.

---

## 🎯 Objective

To build an **unsupervised machine learning model** using **K-Means Clustering** that identifies distinct customer segments based on features like age, income, and spending score.

---

## 🧾 Dataset Description

The dataset used is **Mall\_Customers.xls**, which contains data about customers of a mall.

### Features:

* `CustomerID` – Unique identifier
* `Gender` – Male/Female
* `Age` – Customer age
* `Annual Income (k$)` – Income in thousands of dollars
* `Spending Score (1-100)` – Score assigned by the mall based on customer behavior

---

## 🛠️ Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib, Seaborn (for visualization)
* Scikit-learn
* `xlrd` or `openpyxl` (for reading `.xls` files)

---

## 🔍 Project Workflow

### 1. 📊 Data Preprocessing

* Load the `.xls` file using `pandas.read_excel()`
* Check for missing values or inconsistencies
* Convert categorical variables (e.g., Gender) to numerical
* Normalize or scale data (optional)

### 2. 📈 Exploratory Data Analysis (EDA)

* Visualize distributions (e.g., Age, Income)
* Analyze customer behavior by Gender, Age, and Spending Score
* Create scatterplots and pairplots to understand data patterns

### 3. 🧠 Apply K-Means Clustering

* Use the **Elbow Method** to determine the optimal number of clusters
* Fit the **KMeans** algorithm on selected features (e.g., Income vs. Spending Score)
* Predict cluster labels for each customer

### 4. 📊 Visualize Clusters

* 2D scatter plots to show customer segments
* Use color to represent different clusters
* Label axes and centroids for interpretation

---


## ✅ Outputs

* Elbow plot showing optimal `k`
* Cluster assignments for each customer
* Cluster visualization plots (2D)

---

## 🔧 Future Enhancements

* Use PCA for dimensionality reduction and 3D cluster visualization
* Deploy the segmentation as an interactive dashboard using Streamlit
* Test with other clustering algorithms (e.g., DBSCAN, Hierarchical)


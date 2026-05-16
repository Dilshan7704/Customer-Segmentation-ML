# 🛍️ Mall Customer Segmentation Clustering

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Clustering-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-teal?style=for-the-badge)
![KMeans](https://img.shields.io/badge/KMeans-Clustering-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

### 🚀 Machine Learning Clustering Project for Customer Segmentation

Customer segmentation using **KMeans Clustering**, **EDA**, **Data Visualization**, and **Unsupervised Machine Learning** techniques.

</div>

---

# 📌 Project Overview

This project focuses on segmenting mall customers into different groups based on their spending behavior and annual income.

The project includes:

✔ Data Cleaning & Preprocessing  
✔ Exploratory Data Analysis (EDA)  
✔ Data Visualization  
✔ Outlier Detection  
✔ Feature Scaling  
✔ KMeans Clustering  
✔ Elbow Method Analysis  
✔ Silhouette Score Evaluation  
✔ Cluster Visualization  
✔ Customer Segment Prediction System  

---

# 🗂️ Project Structure

```bash
MALL-CUSTOMER-SEGMENTATION/
│
├── 📁 data set/
│   └── Mall_Customers.csv
│
├── 📁 src/
│   └── mall_customer_segmentation.ipynb
│
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📄 README.md
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| KMeans | Customer Clustering |

---

# 📊 Exploratory Data Analysis (EDA)

Extensive EDA was performed to understand customer behavior and spending patterns.

### 🔍 EDA Includes

- Missing Value Analysis
- Duplicate Detection
- Gender Distribution Analysis
- Distribution Analysis
- Outlier Detection
- Correlation Analysis
- Pairplot Visualization

---

# 📈 Visualizations

The project includes multiple visualizations such as:

✅ Gender Distribution Countplot  
✅ Histogram Distributions  
✅ Annual Income vs Spending Score Scatterplot  
✅ Pairplots  
✅ Boxplots for Outlier Detection  
✅ Correlation Heatmaps  
✅ Cluster Visualization Scatterplots  

---

# 🧹 Data Preprocessing

The preprocessing pipeline includes:

- Feature Selection
- Outlier Removal
- Feature Scaling using StandardScaler
- Data Preparation for Clustering

---

# 🤖 Clustering Algorithm

The following clustering algorithm was implemented:

| Algorithm | Status |
|---|---|
| KMeans Clustering | ✅ Best Model |

---

# 📌 Finding Optimal Clusters

Two techniques were used to determine the optimal number of clusters:

## ✅ Elbow Method

Used WCSS (Within-Cluster Sum of Squares) to identify the optimal k-value.

## ✅ Silhouette Score

Used Silhouette Score evaluation to measure clustering quality.

---

# 🏆 Final Model

## ✅ KMeans Clustering (k = 5)

The final clustering model segmented customers into 5 different customer groups.

### Features Used

- Annual Income (k$)
- Spending Score (1-100)

---

# 📌 Evaluation Metric

The clustering model was evaluated using:

- Silhouette Score

```python
silhouette_score(X_scaled, cluster_labels)
```

---

# 📊 Cluster Interpretation

Customer groups were analyzed using:

- Mean Profile Analysis
- Median Profile Analysis
- Cluster Size Analysis

These insights help identify:

- High-value customers
- Budget customers
- Premium spenders
- Average customers
- Low spending customers

---

# 🔮 Customer Segment Prediction System

A custom prediction function was implemented to assign new customers into clusters.

```python
assign_cluster_segment()
```

### Example Prediction

```python
new_customer = assign_cluster_segment(
    50,
    100,
    scaler,
    kmeans
)
```

---

# ▶️ Installation & Usage

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/MALL-CUSTOMER-SEGMENTATION.git
```

---

## 2️⃣ Navigate to Project

```bash
cd MALL-CUSTOMER-SEGMENTATION
```

---

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
src/mall_customer_segmentation.ipynb
```

---

# 📚 Dataset Information

Dataset used for this project:

🔗 https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data

---

# 📌 Dataset Features

| Feature | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Gender | Male / Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending behavior score |

---

# 🎯 Objective

The goal of this project is to group customers into meaningful segments for better business decision-making and marketing strategies.

---

# 🚀 Future Improvements

Planned future enhancements:

- 🌐 Streamlit Dashboard
- 📊 Interactive Customer Analytics
- ☁ Cloud Deployment
- 📱 Web Application
- 🔍 Advanced Clustering Algorithms
- 🤖 AI-Based Recommendation System

---

# 📷 Clustering Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
EDA & Visualization
     ↓
Outlier Detection
     ↓
Feature Scaling
     ↓
KMeans Clustering
     ↓
Elbow Method
     ↓
Silhouette Evaluation
     ↓
Cluster Visualization
     ↓
Customer Segmentation
```

---

# 👨‍💻 Author

## Dilshan Nethmin Wijayarathne

💡 Machine Learning Enthusiast  
💻 Full Stack Developer  
📊 Data Analytics & AI Projects  

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
🛠️ Contribute to improvements  

---

<div align="center">

## 🚀 Thanks for Visiting

### 🛍️ Mall Customer Segmentation using Machine Learning

</div>

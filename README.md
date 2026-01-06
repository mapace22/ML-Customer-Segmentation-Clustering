# Customer Segmentation for Sports Marketing | Clustering Analysis

## 📌 Project Overview
The goal of this project is to help **RiseData** identify distinct profiles among individual athletes. By grouping customers with similar behaviors, the company can design personalized marketing strategies, increase loyalty, and optimize the Customer Lifetime Value (CLV).

## 📊 Methodology: K-Means Clustering
Since the dataset lacks predefined labels, I implemented **K-Means**, an unsupervised learning algorithm that groups data points based on their similarity in features like:
- **Annual Income**
- **Spending Score** (Purchase behavior rating)
- **Age**

## 🛠️ Data Science Workflow
1. **Exploratory Data Analysis (EDA):** Visualized distributions and identified the relationship between Income and Spending Score as the primary driver for segmentation.
2. **Optimal Cluster Identification:** Used the **Elbow Method** to find the "point of inflection," determining that **5 clusters** provide the best balance between complexity and interpretability.
3. **Profiling:** Analyzed the centroids of each cluster to define their socioeconomic profile.

## 📉 Strategic Clusters Identified
| Segment | Profile | Marketing Strategy |
| :--- | :--- | :--- |
| **VIP Clients** | High Income / High Spending | Exclusive loyalty programs & early access. |
| **Potential High-Value** | Low Income / High Spending | Targeted promotions to maintain frequency. |
| **Underutilized** | High Income / Low Spending | Market research to understand lack of engagement. |
| **Typical Clients** | Average Income / Average Spending | Retention campaigns to prevent churn. |
| **Low-Value** | Low Income / Low Spending | Minimal investment; prioritize other segments. |



## 📂 Repository Structure
- `/notebooks`: `M7_Marcel_Palma_Parte II_Cluster.ipynb` (Analysis & Modeling).
- `/data`: `Clientes.csv` (Dataset).
- `/docs`: Project requirements and business context.

## 🚀 Technologies Used
- **Python** (Pandas, NumPy)
- **Scikit-Learn** (KMeans)
- **Matplotlib & Seaborn** (Clustering Visualization)


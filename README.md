# 🏘️ Swedish Kommun Clustering with K-Means and PCA

This project applies unsupervised learning using K-Means clustering on municipality-level Swedish data, including metrics like revenue, productivity, population, and infrastructure.

We aim to group municipalities into meaningful clusters and visualize their similarities using **Principal Component Analysis (PCA)**.

---

## 🎯 Objectives

- Apply K-Means clustering on multivariate regional data
- Use the Elbow method to select the optimal number of clusters
- Reduce dimensions using PCA for 2D visualization
- Identify regional trends and differences between kommun groups

---

## 🗂️ Project Files

| File | Description |
|------|-------------|
| `kmeans_clustering.ipynb` | ✅ Main notebook with data loading, elbow method, clustering, and visualization |
| `ikea_kommun_data.txt` | 📄 Input data file (cleaned version of Swedish municipal dataset) |
| `elbow_plot.png` | 📉 Scree plot (WCSS vs k) for optimal cluster selection |
| `cluster_2D_PCA.png` | 🎯 PCA plot of clustered kommun data in 2D |
| `LICENSE` | 🔓 MIT License (optional but recommended) |

---

## 🧠 Techniques Used

- 📊 **K-Means Clustering**
- ⚙️ **WCSS** for elbow method
- 🧮 **PCA** for dimensionality reduction
- 🧼 Preprocessing and normalization (if applied)
- 📈 Visualizations with `matplotlib`

---

## 🔍 Dataset Info

**Columns include**:
- Revenue
- Employees
- Productivity
- Population
- Sales Index
- University education %
- Infrastructure score
- Border type (0/1)

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib

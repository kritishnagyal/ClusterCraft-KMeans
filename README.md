# 🌸 KMeans Clustering on Iris Dataset

This repository demonstrates how to use the **KMeans Clustering** algorithm — a fundamental technique in **Unsupervised Machine Learning** — applied to the famous **Iris dataset**. This project is implemented in a **Jupyter Notebook** using **Python** and **scikit-learn**.

---

## 🧠 What is Unsupervised Learning?

Unlike supervised learning, where the data is labeled, **unsupervised learning** involves training a model on data that has **no labels**. The model tries to identify **patterns or groupings** in the data automatically.

One of the most popular unsupervised techniques is **Clustering**.

---

## 📌 What is KMeans Clustering?

**KMeans** is an iterative clustering algorithm that tries to partition the dataset into **K pre-defined distinct non-overlapping subgroups (clusters)**. The data points in each cluster are **similar to each other** and **different from data points in other clusters**.

### 🔍 How KMeans Works:

1. **Initialization**:
   - Choose the number of clusters `K`.
   - Randomly select `K` centroids (initial cluster centers).

2. **Assignment Step**:
   - Assign each data point to the nearest centroid based on distance (usually **Euclidean distance**).

3. **Update Step**:
   - Calculate new centroids by taking the **mean** of all points assigned to each cluster.

4. **Repeat** the Assignment and Update steps until:
   - The centroids no longer change significantly, or
   - A maximum number of iterations is reached.

### ✅ Key Features:
- Simple and fast
- Sensitive to initial placement of centroids
- Works best on spherical, well-separated clusters

---

## 📁 Repository Structure

```bash
├── Iris.csv                    # Dataset file
├── KMeans_Algorithm.ipynb      # Jupyter Notebook implementing KMeans
└── README.md                   # Project documentation

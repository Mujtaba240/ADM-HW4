# **ADM Homework 4 - MovieLens Dataset Usage for recommendation system**

---

## **Homework Overview**

This repository contains a single file: **`main.ipynb`**, which includes the entire implementation for **Homework 4** of the **ADM Course**. The project is divided into two major tasks:  

1. **MovieLens Dataset Clustering and Analysis**
2. Dataset link: https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?select=rating.csv
3. **Game Strategy Optimization for Arya and Mario**

---

## **1. MovieLens Dataset Clustering and Analysis**

### **Objective:**  
- Perform feature engineering, dimensionality reduction, and clustering on the MovieLens dataset.  
- Use clustering algorithms such as:
  - **K-means**
  - **K-means++**
  - **Gaussian Mixture Model (GMM)**
  - **HDBSCAN**  
- Evaluate and compare clustering results using metrics such as:
  - **Silhouette Score**
  - **Davies-Bouldin Index (DBI)**  

---

### **Key Sections Implemented:**  
- Data Preprocessing and Feature Engineering  
- Dimensionality Reduction (PCA)  
- Clustering Implementation (from scratch and libraries)  
- Optimal Cluster Selection using Elbow and Silhouette Methods  
- Visualization of Clustering Results  
- Comparison of Algorithms Based on Evaluation Metrics  

---

## **2. Game Strategy Optimization (Arya vs Mario)**

### **Objective:**  
- Implement an **optimal game strategy** using:
  - **Recursive Algorithm (Exponential Time)**  
  - **Memoization with Dynamic Programming (Polynomial Time)**  
  - **Minimax Algorithm with Alpha-Beta Pruning (Suggested by LLM)**  

---

### **Key Sections Implemented:**  
- **Recursive Game Strategy:** Find optimal moves for Arya and Mario.  
- **Memoization Optimization:** Reduce time complexity from **O(2^N)** to **O(N²)**.  
- **Minimax with Alpha-Beta Pruning:** Use a game-theoretic approach to improve efficiency.  
- **Comparative Analysis:** Compare runtime, scores, and performance of all three methods.  

---

## **How to Use:**  
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mujtaba240/ADM-HW4.git

# Dimensionality Reduction Techniques: Comparative Analysis

## Objective:
This report presents a comparative analysis of four dimensionality reduction techniques (SVD, PCA, Isomap, and MDS) applied to the Spambase dataset. The goal is to understand the effectiveness of each technique in preserving the original data structure and how well they perform in clustering.

---

## 1. Data Preprocessing

The Spambase dataset was first preprocessed using standard scaling and normalization techniques. The features were scaled to ensure that they were on the same scale and normalized to improve the effectiveness of the dimensionality reduction methods.

---

## 2. Visualizations

### a. **Singular Value Decomposition (SVD)**
- **Visualization:**
   

  ![SVD](https://github.com/vans1836/ML_LAB/blob/main/Screenshot%202024-09-30%20at%2011.03.40%20PM.png)
  
    

### b. **Principal Component Analysis (PCA)**
- **Visualization:**
 ![PCA](https://github.com/vans1836/ML_LAB/blob/main/Screenshot%202024-09-30%20at%2011.06.47%20PM.png)



### c. **Isomap**
- **Visualization:**
-  ![ISOMAP](https://github.com/vans1836/ML_LAB/blob/main/Screenshot%202024-09-30%20at%2011.11.25%20PM.png)
   

### d. **Multidimensional Scaling (MDS)**
- **Visualization:**
  ![MDS](https://github.com/vans1836/ML_LAB/blob/main/Screenshot%202024-09-30%20at%2011.11.45%20PM.png)

---

## 3. Clustering Comparisons

After applying each dimensionality reduction technique, K-means clustering was used to cluster the data in the reduced space. Below is a comparison of the clustering results based on different techniques:

### a. **Singular Value Decomposition (SVD)**
- **Clustering Result:** 
    SVD Silhouette Score: 0.8904858999224924

### b. **Principal Component Analysis (PCA)**
- **Clustering Result:** 
  PCA Silhouette Score: 0.8904860456690384
   

### c. **Isomap**
- **Clustering Result:** 
  Isomap Silhouette Score: 0.678171869255203

### d. **Multidimensional Scaling (MDS)**
- **Clustering Result:** 
   MDS Silhouette Score: 0.27359770497062497
---

## 4. Discussion

### Advantages and Limitations of Each Method

**Singular Value Decomposition (SVD):**
- **Advantages:**
    - Reduces data dimensionality effectively.
    - Works well when the data matrix is well-structured.
- **Limitations:**
    - May lose interpretability with high-dimensional datasets.

**Principal Component Analysis (PCA):**
- **Advantages:**
    - Captures the variance in the data effectively.
    - Fast and efficient for large datasets.
- **Limitations:**
    - May struggle with non-linear relationships.

**Isomap:**
- **Advantages:**
    - Captures non-linear relationships.
    - Useful for preserving geodesic distances.
- **Limitations:**
    - May be computationally expensive for large datasets.

**Multidimensional Scaling (MDS):**
- **Advantages:**
    - Useful for visualizing the structure of high-dimensional data.
    - Preserves pairwise distances between points.
- **Limitations:**
    - Can be slow on large datasets
 
      ## Analysis
Both SVD and PCA performed excellently in clustering the Spambase dataset, indicating their effectiveness in preserving the underlying data structure during dimensionality reduction. Isomap provided moderate performance, while MDS struggled significantly, demonstrating its limitations in this context.


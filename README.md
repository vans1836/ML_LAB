# ML_LAB
# Exercise 1: Comparative Analysis of Dimensionality Reduction Techniques

## Objective:
The goal of this exercise is to apply four different dimensionality reduction techniques (SVD, PCA, Isomap, MDS) on the Spambase dataset. We will preprocess the data, apply each technique, and compare the effectiveness of each method in preserving the original data structure by evaluating clustering or classification performance.

## Tasks:
1. **Select Dataset:**
   - The dataset can be accessed from the UCI Machine Learning Repository [Spambase Dataset](https://archive.ics.uci.edu/dataset/94/spambase).
   
2. **Preprocess the Data:**
   - Perform data scaling and normalization to ensure that the features are on the same scale.

3. **Implement Dimensionality Reduction Techniques:**
   - Apply the following dimensionality reduction techniques:
     - **SVD (Singular Value Decomposition)**
     - **PCA (Principal Component Analysis)**
     - **Isomap**
     - **MDS (Multidimensional Scaling)**

4. **Visualize the Results:**
   - Create visualizations to represent the reduced data obtained from each technique.

5. **Evaluate and Compare Effectiveness:**
   - Use K-means clustering to evaluate how well each technique preserves the structure of the original data.
   - Compare the clustering results across the different techniques.

## Spambase Dataset:
- **Description:** The Spambase dataset contains emails labeled as spam or non-spam, with various features related to the content. It can be used for classification tasks and exploratory analysis.
- **Link to Dataset:** [Spambase Dataset](https://archive.ics.uci.edu/dataset/94/spambase)

## Deliverable:
- A report with:
  - Visualizations for each dimensionality reduction technique.
  - Comparisons of clustering results for each technique.
  - A discussion on the advantages and limitations of each method.

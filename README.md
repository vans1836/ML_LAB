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

# Exercise 2: Dimensionality Reduction for Image Compression

## Objective:
In this exercise, we aim to use PCA or SVD to compress an image dataset and evaluate the effectiveness of reconstructing the compressed images. We will use the CIFAR-10 dataset for this task.

## Tasks:
1. **Select Image Dataset:**
   - The dataset chosen is the [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html).

2. **Implement PCA or SVD for Dimensionality Reduction:**
   - Reduce the dimensionality of the images using:
     - **PCA (Principal Component Analysis)** or
     - **SVD (Singular Value Decomposition)**.

3. **Reconstruct Images:**
   - Reconstruct the original images from the reduced representations obtained from PCA or SVD.

4. **Compare Quality:**
   - Evaluate the quality of the original images and the reconstructed images using metrics like:
     - **Mean Squared Error (MSE)**.
     - **Structural Similarity Index (SSIM)**.

## CIFAR-10 Dataset:
- **Description:** The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes, commonly used for image classification tasks.
- **Link to Dataset:** [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)

## Deliverable:
- A comprehensive analysis that includes:
  - Compression ratio achieved by reducing the image dimensionality.
  - Quality of the reconstructed images compared to the original images.
  - Visual examples of the original and reconstructed images.
  - Performance evaluation using MSE and SSIM to quantify the differences.



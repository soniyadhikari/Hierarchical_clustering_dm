# Hierarchical Clustering for Document Clustering

## 📌 Overview

This project explores **Hierarchical Clustering**, an unsupervised machine learning technique used to group similar data points into clusters.

The project applies hierarchical clustering to text documents using Natural Language Processing (NLP) techniques. It demonstrates how text data can be transformed into numerical features and grouped based on similarity.

## 🎯 Objectives

- Understand the concept of hierarchical clustering.
- Perform text preprocessing and feature extraction.
- Represent documents using TF-IDF.
- Apply dimensionality reduction to simplify document representations.
- Visualize and evaluate clustering results.

## 🛠️ Technologies Used

- **Python**
- **Google Colab / Jupyter Notebook**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **SciPy**
- **TF-IDF Vectorization**
- **Truncated SVD**

## 📂 Project Structure

```text
Hierarchical_clustering_dm/
│
├── hierarchical_clustering.ipynb
└── README.md
```

*Note: The notebook filename above is an example. Replace it with your actual uploaded filename if it differs.*

## ⚙️ Methodology

### 1. Dataset

The project uses text documents from the 20 Newsgroups dataset, a collection commonly used for text classification and clustering experiments.

### 2. Text Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) converts text documents into numerical feature vectors based on the importance of words.

### 3. Dimensionality Reduction

Truncated Singular Value Decomposition (SVD) can reduce the dimensionality of the TF-IDF feature matrix while retaining useful information.

### 4. Hierarchical Clustering

Agglomerative hierarchical clustering groups similar documents by progressively merging clusters. Ward linkage can be used to minimize the increase in within-cluster variance.

### 5. Evaluation

Clustering performance can be evaluated using metrics such as:

- **Silhouette Score:** Measures how well-separated the clusters are.
- **Adjusted Rand Index (ARI):** Compares predicted clusters with known labels.
- **Davies–Bouldin Index (DBI):** Measures cluster compactness and separation.

These metrics are useful for analyzing the quality of the resulting clusters.

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install any required libraries if they are not already available.
3. Run the notebook cells in order.
4. Review the clustering results, visualizations, and evaluation metrics.

## 📚 Key Learning Outcomes

- Understanding unsupervised learning and document clustering.
- Learning how to represent text data numerically using TF-IDF.
- Exploring dimensionality reduction using SVD.
- Understanding agglomerative clustering and linkage methods.
- Evaluating clustering results using internal and external metrics.

## 👩‍💻 Author

**Soniya Adhikari**

Computer Engineering  
IOE Pashchimanchal Campus, Nepal

## 📄 License

This project is available for educational and learning purposes. Add a specific open-source license if you intend to formally license the code.

# 🧠 Clustering Playground: Unsupervised Learning Lab

<p align="center">
  <img src="https://img.shields.io/badge/status-complete-brightgreen" />
  <img src="https://img.shields.io/badge/language-Python-blue" />
  <img src="https://img.shields.io/badge/tech-Numpy%20%7C%20Matplotlib%20%7C%20Scikit--learn-orange" />
</p>

## 📘 Overview

This project is a hands-on lab from **NYU Paris (Summer 2023)** focused on unsupervised machine learning techniques. You’ll find practical implementations of:

- 🧮 K-means Clustering
- 🌲 Hierarchical Clustering
- 📊 Gaussian Mixture Models (GMM)

The notebook walks you through visual, intuitive examples using Python libraries like `numpy`, `matplotlib`, and `sklearn`.

## 🎯 Goals

- Practice unsupervised learning techniques
- Understand clustering pros & cons
- Build from scratch and visualize the clustering process

## 🧪 Technologies

- Python 3
- Numpy
- Scikit-learn
- Matplotlib

## 🧩 How it Works

This notebook answers real questions like:

- How do I initialize centroids in K-means?
- How are labels assigned to data points?
- Can I visualize how clustering works?
  
Key functions implemented:
```python
init_centroids(K, dimension=2)
assign_labels(X, centroids)
plot_kmeans(X, labels, centroids)
````

## 📁 File Structure

```bash
📦Clustering-Lab
 ┣ 📄clustering.ipynb       # The Jupyter notebook with full code and exercises
 ┣ 📄README.md              # This file
 ┗ 📊output_3_0.png         # Sample visualization output
```

## 📸 Sample Visualization

The dataset is synthetic and clustered using `make_blobs()` for clear visual understanding. Below is an example of clustered output:

<p align="center">
  <img src="./output_3_0.png" width="60%" />
</p>

## 👨‍🏫 Author

* 👨‍💼 Guillaume Staerman (Instructor)
* 📝 Notebook enhanced and prepared for GitHub by contributors


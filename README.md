# Clustering Project

This project showcases the implementation of clustering algorithms, including **KMeans**, **Hierarchical Clustering**, and **Mean Shift Clustering**. The scripts leverage preprocessing techniques and evaluation metrics to analyze and visualize clustering results effectively.

---
## Authors

- [@Guryansh](https://www.github.com/Guryansh)
  

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Guryansh/Clustering-Assignment
   cd your-repo-name
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

> **Note:** Ensure Python 3.7+ is installed on your system.

---

## Usage

These notebooks:
- Loads the Facebook dataset.
- Applies KMeans clustering, Hierarchical clustering and KMean Shift clustering for cluster counts (3, 4, 5).
- Evaluates performance using metrics like Silhouette, Calinski-Harabasz, and Davies-Bouldin scores.
- Saves result tables in the folder.

---

## Key Features

### Preprocessing Techniques
- **Normalization**: Z-score standardization.
- **Transformation**: Yeo-Johnson transformation.
- **Dimensionality Reduction**: PCA with linear kernel.

### Metrics Evaluated
- **Silhouette Score**: Measures cohesion and separation of clusters.
- **Calinski-Harabasz Index**: Evaluates cluster dispersion.
- **Davies-Bouldin Index**: Indicates cluster compactness and separation.

### Visualizations
- Metric comparison tables.
---

## Results Overview

![download (4)](https://github.com/user-attachments/assets/ed6c1a4b-8d17-4fe5-9501-120eaee20a27)

---

## Dependencies

- Python 3.7+
- PyCaret
- Pandas
- Matplotlib

---

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

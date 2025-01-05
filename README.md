
# Wholesale Customers Data Analysis and Machine Learning Models

This project involves data analysis and the application of both supervised and unsupervised machine learning techniques on the Wholesale Customers dataset. The goal is to analyze the data, classify spending behavior, and cluster customers based on purchasing patterns.

---

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Supervised Learning](#supervised-learning)
6. [Unsupervised Learning](#unsupervised-learning)
7. [Results](#results)


---

## Overview

The project uses various machine learning algorithms to gain insights into the purchasing behavior of wholesale customers. It includes:

1. Data exploration and visualization.
2. Supervised learning for classifying spending categories.
3. Unsupervised learning for customer clustering.

---

## Dataset

The dataset contains the following features:
- **Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicassen**: Quantities spent on various product categories.
- **Channel**: Distribution channel (1 = Horeca, 2 = Retail).
- **Region**: Geographic region (1 = Lisbon, 2 = Porto, 3 = Other).

Target variable for classification: Spending Category (`Low`, `Medium`, `High`).

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/wholesale-customers-analysis
   cd wholesale-customers-analysis
   ```

2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset (`Wholesale customers data.csv`) in the project directory.

---

## Usage

Run the Python script in jupyter notebook to perform data analysis and machine learning tasks:
```bash
final_code.ipynb
```

The script performs:
- Data preprocessing and visualization.
- Training and evaluation of supervised classification models.
- Clustering using unsupervised techniques (K-Means and Hierarchical Clustering).

---



---

## Supervised Learning

The supervised classification task involves predicting spending categories (`Low`, `Medium`, `High`) using:
1. **Random Forest Classifier**
2. **Bagging Classifier**
3. **AdaBoost Classifier**
4. **XGBoost Classifier**
5. **CatBoost Classifier**

### Evaluation Metrics:
- Accuracy
- Confusion Matrix
- Classification Report

A bar chart compares model accuracies.

---

## Unsupervised Learning

### K-Means Clustering:
1. Optimal number of clusters determined using the Elbow Method and Silhouette Scores.
2. Visualized clusters with PCA-reduced components.

### Hierarchical Clustering:
1. Dendrogram to visualize cluster merging.
2. Cluster visualization with PCA-reduced components.

---

## Results

### Supervised Learning:
The best model and its performance are printed in the script.

### Unsupervised Learning:
Cluster insights are visualized using PCA for both K-Means and Hierarchical Clustering.



# Self-Organizing Maps for Customer Cluster Analysis
This project uses a Self-Organizing Map (SOM) - an unsupervised machine learning clustering algorithm - to cluster customer data. The goal is to separate customers into distinct classes that capture similar behaviors and characteristics.

## 📁 Project Structure
```
├── cluster.ipynb
├── README.md
├── requirements.txt
```

## 📊 Overview
This notebook includes the following steps:
* Loading the dataset from Kaggle
* Exploring the categorical and numerical features in the data
* Performing preprocessing steps (normalization, one-hot encoding) on the data
* Clustering using SOM
* Dimensionality reduction with UMAP
* Visualizing the resultant cluster

## 📃 Data Description
We use [Vijay Choudhary's Mall Customer Segmentation dataset from Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

## 💻 Installation
Create and activate a Python virtual environment and run the following command:
```
pip install -r requirements.txt
```

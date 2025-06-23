# SCT_ML_02
Mall Customer Segmentation with K-means Clustering
Overview
This project applies the K-means clustering algorithm to segment customers of a retail store based on their annual income and spending score. The goal is to identify distinct customer groups to help the business tailor its marketing strategies.

Dataset
Name: Mall Customer Dataset

Source: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

Features Used:

Annual Income (k$)

Spending Score (1-100)

Project Structure
text
├── data/
│   └── Mall_Customers.csv
├── src/
│   └── kmeans_clustering.py
├── README.md
└── requirements.txt
Getting Started
Prerequisites
Python 3.x

pandas

numpy

matplotlib

scikit-learn

Install dependencies using pip:

bash
pip install -r requirements.txt
Running the Project
Clone the repository:

bash
git clone https://github.com/your-username/mall-customer-segmentation.git
cd mall-customer-segmentation
Place the dataset (Mall_Customers.csv) in the data/ directory.

Run the clustering script:

bash
python src/kmeans_clustering.py
View the output:
The script will display a scatter plot showing customer segments and save cluster labels to the dataset.

Results
Customers are grouped into clusters based on their annual income and spending score.

The resulting segments can be visualized to identify high-value and low-value customer groups.



Usage
You can modify the number of clusters or features in src/kmeans_clustering.py to experiment with different segmentations.

References
scikit-learn K-means documentation

Mall Customer Segmentation Dataset on Kaggle

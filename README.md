# E-Commerce Customer Segmentation & Recommendation Analysis

## Project Overview
This project analyzes e-commerce transaction data to understand customer purchasing behavior, segment customers using Machine Learning, and recommend similar products using Cosine Similarity.

## Objectives
- Analyze customer purchasing patterns.
- Perform RFM (Recency, Frequency, Monetary) analysis.
- Segment customers using K-Means Clustering.
- Identify customer groups and their characteristics.
- Recommend similar products using Cosine Similarity.
- Provide business strategies for different customer segments.

## Dataset
**Source:** UCI Machine Learning Repository – Online Retail Dataset

The dataset contains transaction records from an online retail store.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Techniques
- RFM Analysis
- StandardScaler
- K-Means Clustering
- PCA (Principal Component Analysis)
- Cosine Similarity

## Project Structure
```text
E_Commerce/
├── data/
│   ├── Online Retail.xlsx
│   ├── cleaned_transactions.csv
│   ├── customer_features.csv
│   ├── customer_segments.csv
│   └── product_recommendations.csv
├── notebooks/
│   └── E_Commerce_Customer_Analysis.ipynb
├── visualizations/
│   ├── elbow_method.png
│   ├── silhouette_analysis.png
│   ├── customer_clusters.png
│   └── customer_segments.png
├── README.md
└── requirements.txt
```

## Key Features
1. Data cleaning and preprocessing.
2. Customer behavior analysis using RFM.
3. Customer segmentation into five groups using K-Means.
4. Product recommendations based on purchasing similarity.
5. Visualizations and business recommendations.

## Results
- Analyzed 392,692 cleaned transactions.
- Identified 4,338 unique customers.
- Created five customer segments.
- Generated product recommendations for popular products.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install -r requirements.txt`
3. Open the Jupyter Notebook in the `notebooks` folder.
4. Run the cells in order.

## Conclusion
This project demonstrates how data analysis and machine learning can help e-commerce businesses understand customer behavior, identify valuable customer groups, and improve product recommendations.

## Author
CSE Student | Python & Machine Learning Project
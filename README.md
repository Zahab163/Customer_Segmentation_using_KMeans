# Customer_Segmentation_using_K-Means Clustering ( A Project of Unsupervised Learning)


## 📚 Overview
This repository contains two comprehensive Jupyter Notebook implementations of customer segmentation using K-Means clustering algorithm. The project focuses on analyzing credit card customer data to identify distinct customer segments based on their spending behavior, credit usage patterns, and demographic characteristics.
**(Live Demo)[https://youtu.be/7oHYJ-e0HNM]

**Author**: Zahabia Ahmed  
**Field**: Artificial Intelligence & Data Science

## 🎯 Project Description
Customer segmentation is a crucial marketing strategy that helps businesses understand their customers better and tailor their services accordingly. This project demonstrates unsupervised learning techniques to group customers into meaningful segments using K-Means clustering.

## 📁 Repository Structure

```
Customer_Segmentation_using_K-Means_Clustering/
│
├── Customer_Segmentation with_Sscore&PCAt.ipynb (done by Kaggle_Dataset)
├── End_to_End_Customer_Segmentation.ipynb( Done by Creating new data set)
├── credit_card_customer_segmentation.csv( downloaded from kaggle)
└── README.md
```

## 📊 Notebooks Description

### 1. Customer_Segmentation_Kaggle_Dataset.ipynb
- **Dataset Source**: Kaggle dataset for customer segmentation
- **Features**: Comprehensive analysis with proper Silhouette Score and PCA implementation
- **Key Components**:
  - Data preprocessing and exploration
  - Optimal cluster determination using Elbow method and Silhouette Score
  - PCA for dimensionality reduction and visualization
  - Detailed cluster analysis and profiling
  - 2D and 3D visualizations of customer segments

### 2. End_to_End_Customer_Segmentation.ipynb
- **Dataset**: Comprehensive synthetic credit card customer data
- **Features**: Complete end-to-end implementation with extensive visualizations
- **Key Components**:
  - Complete data preprocessing pipeline
  - Multiple clustering visualizations
  - Detailed customer segment profiling
  - Comprehensive exploratory data analysis (EDA)
  - Business insights and recommendations

## 🔍 K-Means Clustering - Brief Explanation

K-Means clustering is an unsupervised machine learning algorithm used to partition data into K distinct, non-overlapping clusters. The algorithm works as follows:

### Algorithm Steps:
1. **Initialization**: Randomly select K data points as initial cluster centroids
2. **Assignment**: Assign each data point to the nearest centroid
3. **Update**: Recalculate centroids as the mean of all points in the cluster
4. **Iteration**: Repeat steps 2-3 until convergence (no more changes in assignments)

### Key Concepts:
- **Centroids**: Center points of clusters
- **Within-Cluster Sum of Squares (WCSS)**: Measure of cluster compactness
- **Elbow Method**: Technique to determine optimal number of clusters
- **Silhouette Score**: Measures how similar an object is to its own cluster compared to other clusters

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - pandas, numpy (Data manipulation)
  - scikit-learn (Machine Learning)
  - matplotlib, seaborn (Visualization)
 

## 📈 Key Features

### Data Analysis:
- Customer demographic analysis
- Spending pattern identification
- Credit utilization behavior
- Payment habit analysis

### Clustering Techniques:
- Optimal K selection using multiple methods
- Feature scaling and preprocessing
- Dimensionality reduction using PCA
- Cluster validation metrics

### Visualizations:
- Elbow plots for optimal K determination
- PCA scatter plots (2D and 3D)
- Cluster characteristic heatmaps
- Spending pattern comparisons
- Demographic distributions

## 🎯 Business Applications

The identified customer segments can be used for:

1. **Targeted Marketing**: Customized campaigns for different segments
2. **Product Development**: Tailored credit card features
3. **Risk Management**: Identify high-risk customer groups
4. **Customer Retention**: Personalized retention strategies
5. **Cross-selling**: Relevant product recommendations

## 🚀 How to Use

### Prerequisites:
- Python 3.7+
- Jupyter Notebook
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Steps:
1. Clone the repository
2. Install required dependencies
3. Open the desired notebook in Jupyter
4. Run cells sequentially
5. Analyze the results and visualizations

## 📋 Dataset Information

The dataset contains customer information with features including:
- Demographic data (Age, Gender, Education, Marital Status)
- Financial information (Annual Income, Credit Limit)
- Spending patterns (Transaction details, Category spending)
- Behavioral data (Payment habits, Credit utilization)

## 📊 Results Interpretation

### Cluster Characteristics:
- **High-Value Customers**: High income, high spending, low credit utilization
- **Budget-Conscious**: Moderate income, essential spending, timely payments
- **Risk Profiles**: High credit utilization, payment delays
- **Travel Enthusiasts**: High travel-related spending
- **Conservative Users**: Low credit utilization, minimal spending

### Evaluation Metrics:
- Silhouette Score for cluster quality assessment
- WCSS for cluster compactness
- PCA explained variance for dimensionality reduction effectiveness

## 🔮 Future Enhancements

- Integration with other clustering algorithms (DBSCAN, Hierarchical)
- Real-time customer segmentation
- Deep learning approaches for segmentation
- Customer lifetime value prediction
- Churn prediction modeling

## 👩‍💻 About the Author

i'am **Zahabia Ahmed** and currently pursuing studies in Artificial Intelligence and Data Sciences. This project demonstrates practical implementation of unsupervised learning techniques for real-world business problems.

## 📄 License

This project is for educational purposes. Please ensure proper attribution when using the code or methodology.

---

*For any questions or suggestions, feel free to reach out to the author.*

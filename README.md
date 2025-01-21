
# Credit Card Customer Segmentation

## Overview
This project focuses on segmenting credit card customers using clustering techniques. The objective is to identify distinct customer groups based on their spending behavior and other attributes, enabling businesses to design targeted marketing strategies and optimize customer retention.

## Problem Statement
Customer segmentation is critical for understanding diverse customer needs and improving service offerings. This project applies clustering algorithms to categorize credit card customers into groups based on transactional and demographic data.

## Key Features
- **Data Preprocessing**: Handling missing values, outlier detection, and normalization.
- **Exploratory Data Analysis (EDA)**: Identifying patterns and relationships in customer attributes.
- **Clustering Models**: K-means, Hierarchical Clustering, and DBSCAN are employed to identify customer groups.
- **Evaluation**: Cluster validation using metrics such as silhouette scores and elbow method.

## Tech Stack
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and SciPy.

## Dataset
The dataset includes attributes like:
- Customer ID
- Annual Spending
- Transaction Frequency
- Credit Card Limit
- Other demographic and transactional details.

_Note: Dataset is anonymized to ensure privacy._

## Results
- Optimal clusters determined using the elbow method.
- Customer segments visualized through 2D PCA plots.
- Recommendations provided for marketing and customer engagement strategies.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-clustering.git
   cd credit-card-clustering
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Case_8_Credit_Card_Clustering.ipynb
   ```
4. Execute the cells in sequence.

## File Structure
```
credit-card-clustering/
├── data/
│   └── dataset.csv (if included)
├── notebooks/
│   └── Case_8_Credit_Card_Clustering.ipynb
├── README.md
├── results/
│   └── clustering_visualizations.png
```

## References
- [Silhouette Method for Cluster Validation](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html)
- [DBSCAN Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)

## License
This project is licensed under the MIT License. Feel free to use and modify the code as needed.

## Author
**Tanuj Vijayakumar**  
[LinkedIn](https://www.linkedin.com/in/tanujvijayakumar)  

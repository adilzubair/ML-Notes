# Unsupervised Learning

## Introduction to Unsupervised Learning
- Unsupervised learning involves exploring patterns within data without explicit guidance or labeled examples. It diverges from supervised learning paradigms by solely relying on inherent structures within the dataset for learning.

## Types of Unsupervised Learning
- **Clustering Algorithms**: Techniques like K-Means, Hierarchical Clustering, DBSCAN, and Gaussian Mixture Models segment data into cohesive clusters based on inherent similarities.
- **Dimensionality Reduction Techniques**: Methods such as Principal Component Analysis (PCA), t-Distributed Stochastic Neighbor Embedding (t-SNE), and Autoencoders distill high-dimensional data into a lower-dimensional representation while preserving essential features.

## Clustering Algorithms
- **K-Means Clustering**: A partitioning algorithm that assigns data points to K clusters iteratively, minimizing the intra-cluster variance.
- **Hierarchical Clustering**: Constructs a dendrogram by iteratively merging or splitting clusters based on proximity.
- **DBSCAN**: Identifies clusters as dense regions separated by sparser areas, robust to noise and outliers.
- **Gaussian Mixture Models**: Assumes data points are generated from a mixture of Gaussian distributions, allowing for soft assignment of points to clusters.

## Dimensionality Reduction Techniques
- **PCA**: Finds orthogonal axes capturing the maximum variance in the data, enabling dimensionality reduction while retaining information.
- **t-SNE**: Non-linear dimensionality reduction method emphasizing the preservation of local similarities.
- **Autoencoders**: Neural network architectures that learn to encode data into a lower-dimensional space, then decode it back to the original dimensions.

## Applications of Unsupervised Learning
- **Customer Segmentation**: Identifying distinct groups of customers based on purchasing behavior or demographics.
- **Anomaly Detection**: Detecting outliers or irregularities in data indicative of potential anomalies or errors.
- **Image Compression**: Reducing the size of images while retaining crucial visual information.
- **Topic Modeling**: Uncovering latent topics within a corpus of documents, facilitating document organization and retrieval.

## Evaluation Metrics for Unsupervised Learning
- **Silhouette Score**: Quantifies the compactness and separation of clusters.
- **Davies–Bouldin Index**: Measures the average similarity between clusters, assisting in cluster quality assessment.
- **Adjusted Rand Index (ARI)**: Evaluates the agreement between two clustering results, adjusted for chance.

## Challenges and Considerations
- Determining Optimal Cluster Number: Selecting an appropriate number of clusters without prior knowledge can be challenging.
- Handling High-Dimensional Data: Unsupervised learning is susceptible to the curse of dimensionality, necessitating dimensionality reduction techniques.
- Noise and Outlier Management: Anomalies can significantly impact clustering results, requiring robust algorithms.

## Best Practices
- Preprocessing: Standardize or normalize data before applying unsupervised learning algorithms to ensure fair comparison and convergence.
- Visualization: Utilize visualization tools to comprehend cluster structures and dimensionality-reduced representations effectively.
- Hyperparameter Tuning: Experiment with different hyperparameters to optimize algorithm performance for specific datasets.

```python
# Importing the packages

import pandas as pd
from sklearn.cluster import KMeans
import matplotlib.pyplot as plt
import seaborn as sns

%matplotlib inline

# Importing the dataset
iris=pd.read_csv("iris.csv")

iris.columns

iris.head()

# This shows how comparision of sepal length for different species
sns.boxplot(x = 'species', y='sepal_length', data = iris)

# This shows how comparision of sepal width for different species
sns.boxplot(x = 'species', y='sepal_width', data = iris)

# This shows how comparision of petal length for different species
sns.boxplot(x = 'species', y='petal_length', data = iris)

# This shows how comparision of petal width for different species
sns.boxplot(x = 'species', y='petal_width', data = iris)

## Shows distribution of the variables
iris.hist(figsize=(8,6))
plt.show()


```



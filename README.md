# US Arrests Dataset Analysis - PCA and Clustering
### Overview
This project explores the US Arrests dataset from the 1973 US arrests statistics. The dataset includes the number of arrests per 100,000 residents for Assault, Murder, and Rape in each of the 50 US states, as well as the percentage of the population living in urban areas (UrbanPop).

The analysis involves:

* Exploratory Data Analysis (EDA)
* Principal Component Analysis (PCA) to reduce dimensionality and identify key patterns
* Clustering techniques: K-Means and Hierarchical Clustering to categorise states into groups based on crime rates and urban population
* Visualisation of results

### Dataset
The dataset used in this analysis is UsArrests.csv which contains the following columns:

* `City`: The US state
* `Murder`: Murder arrests per 100,000 residents
* `Assault`: Assault arrests per 100,000 residents
* `UrbanPop`: Percent urban population
* `Rape`: Rape arrests per 100,000 residents

### Key Libraries
* pandas: Data manipulation and analysis
* numpy: Numerical operations
* matplotlib and seaborn: Data visualization
* sklearn: Machine learning, including PCA, scaling, and clustering

### Steps in the Analysis

1. Exploratory Data Analysis (EDA)
* Visualise the distribution of variables using histograms
* Analyse correlations between variables using a heatmap
* Standardise the data for meaningful PCA results

2. Principal Component Analysis (PCA)
* Perform PCA to reduce dimensionality
* Visualise the principal components to identify important features
* Analyse the proportion of variance explained by each component

3. Clustering
* K-Means Clustering: Determine the optimal number of clusters using Elbow and Silhouette methods, then perform K-Means clustering
* Hierarchical Clustering: Use Agglomerative Clustering and visualise results using dendrograms

4. Visualisation
* Generate plots to visualise clusters and feature importance
* Boxplots to compare crime rates across clusters

### Results
* The PCA revealed that the first two principal components explain a significant portion of the variance in the data.
* K-Means and Hierarchical Clustering both suggested two main clusters:
  * Cluster 0: Low-risk states with relatively fewer crimes
  * Cluster 1: High-risk states with higher crime rates

### Conclusion
The analysis provides insights into crime patterns across US states in 1973. It identifies key features that influence crime rates and groups states into clusters with similar crime profiles. The results can help in understanding crime distribution and potentially guide resource allocation for law enforcement.

### Usage
To reproduce the analysis:

* Clone the repository
* Install the required Python libraries (requirements.txt)
* Run the notebook using Jupyter or any compatible environment

--------------------------------------------------------------------------------

#### References: 

https://www.kaggle.com/code/hmahida/usarrests-pca-k-means-and-agglomerative-clustering

https://www.kaggle.com/code/gauravduttakiit/clustering-using-k-means-hierarchical-pca

https://www.kaggle.com/code/ankandash/pca-k-means-clustering-hierarchical-clustering

https://www.kaggle.com/code/halimedogan/usa-arrests-with-k-means-clustering

https://www.kaggle.com/code/kerneler/starter-usarrets-73d905cc-b/notebook

https://stackoverflow.com/questions/28862334/k-means-with-selected-initial-centers

##### Thank you, Farinaaz :)

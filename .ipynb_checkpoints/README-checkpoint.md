# Unsupervised-Learning-Homework
The main task in this challenge is to apply the unsupervised learning tools to analyze the performance of cryptocurrencies. The primary tool utilized is clustering

### Organization
The relavent python notebooks is titled `crypto_investments.ipynb`

### Code and Dependencies
This code is to be run on `Python 3.7.13`

The following Python Libraries were also imported and used:

`import pandas as pd`
`import hvplot.pandas`
`from path import Path`
`from sklearn.cluster import KMeans`
`from sklearn.decomposition import PCA`
`from sklearn.preprocessing import StandardScaler`

## Objectives
- Cluster Cryptocurrencies with K-means Using the Original Data
- Optimize Clusters with Principal Component Analysis
- Find the Best Value for k Using the PCA Data
- Cluster Cryptocurrencies with K-means Using the PCA Data
- Visualize and Compare the Results


## Results and Data Story
The Elbow Curve plots between the original data and the PCA data are the same.
[Repo Link](https://github.com/bweilers/Unsupervised-Learning-Homework) <br>
![Repo Image](./Resources/bokeh_plot1.png)

The Clustering Restults are different, and it appears PCA is useful in helping to identify segments amoung data with a large variety of columns.
[Repo Link](https://github.com/bweilers/Unsupervised-Learning-Homework) <br>
![Repo Image](./Resources/bokeh_plot2.png)

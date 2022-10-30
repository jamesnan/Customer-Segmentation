# Mall Customer Segmentation
## Define the problem

Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately. This is the unsupervised clustering problem and five popular algorithms will be presented and compared: KMeans, Hierarchical, Affinity Propagation and DBSCAN. 

The data set is taken from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?datasetId=42674&sortBy=voteCount). It consists customers information related to their age, gender, annual income, and spending score. The spending score is a numeric variable ranging from 1 to 100 and was assigned to customers based on behavior parameters and purchasing data. 

## Steps to solve the problem:
1. Importing Libraries<br>
2. Loading the Dataset<br>
3. Exploratory Data Analysis<br>
   3.1 Distribution of values in Age , Annual Income and Spending Score<br>
   3.2 Correlations between numerical variables<br>
4. Clustering]<br>
   4.1 K-Means Clustering<br>
   &nbsp;&nbsp;&nbsp;&nbsp; 4.1.1 K-Means 5 Clusters<br>
   &nbsp;&nbsp;&nbsp;&nbsp; 4.1.2 K-Means 6 Clusters<br>
   4.2 Fuzzy C-Means Clustering]<br>
   4.3 DBSCAN (Density Based Spatial Clustering of Applications with Noise)<br>
   4.4 Heirarchal (Agglomerative)<br>
   4.5 Affinity Propagation<br>   
5. Comparison and Conclusion<br>

## Built with
* numpy
* pandas 
* seaborn
* matplotlib
* sklearn
* scipy
* yellowbrick
* mpl_toolkits.mplot3d

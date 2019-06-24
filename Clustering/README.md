# Clustering

## K means clustering

### Points to remember
* Starting centroid matters
* Final results are not same regardless of start

#### For understanding only 
* For that scikit learn run kmeans many times with random starting point
* If it end up with different point than we choose best grouping. 
* Best grouping for cluster k is defined as grouping with avg dist from the points to its corresponding centroids is the smallest.

## Feature Scaling
For any machine learning algorithm that uses distances as a part of its optimization, it is important to scale your features.

### Most Common
* Normalizing or Max-Min Scaling - this type of scaling moves variables between 0 and 1
* Standardizing or Z-Score Scaling - this type of scaling creates variables with a mean of 0 and standard deviation of 1

### Advantage
* Without feature scaling features with much larger variance dominates on features with small variance which we don't want
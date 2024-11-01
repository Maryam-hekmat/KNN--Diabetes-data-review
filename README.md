# KNN--Diabetes-data-review
We want to do a simple test to check whether the neighbor and nearest neighbor method is useful for our diabetes data. With KNN method. Supervised learning
 KNN (K-Nearest Neighbors)
KNN (K-Nearest Neighbors) is a supervised machine learning algorithm used for classification and regression. This algorithm makes decisions based on the proximity of data to their nearest neighbors. The working principles of KNN are as follows:

Choosing the value of K: First, we determine the number of nearest neighbors (K).

Distance calculation: We calculate the distance of each sample with the existing training samples. Euclidean distance is usually used.

Selection of nearest neighbors: we select the nearest K samples.

Classification/Prediction: The dominant class among K neighbors for classification or the mean values ​​for regression is selected as prediction.

In the diabetes dataset we examined, the KNN algorithm was not efficient. This may be due to:

High dispersion: the data were not well separated by KNN.

High dimensions: KNN algorithm is less efficient in high dimensions.

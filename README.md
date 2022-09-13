# K-Nearest Neighbour (KNN)
- K-Nearest Neighbour (KNN) is one of the simplest Machine Learning algorithms based on **Supervised Learning technique**
- KNN is a type of supervised learning algorithm used for both **regression and classification**, but mostly it is used for the Classification problems.
- KNN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is **most similar** to the available categories.
 
![Image](https://static.javatpoint.com/tutorial/machine-learning/images/k-nearest-neighbor-algorithm-for-machine-learning2.png)

## The KNN Algorithm
- Load the data
- Initialize **K** to your chosen number of neighbors
- Calculate the **Euclidean distance** of K number of neighbors
- Take the K nearest neighbors as per the calculated Euclidean distance.
- Among these k neighbors, count the number of the data points in each category.
- Assign the new data points to that category for which the number of the neighbor is maximum.

Suppose we have a new data point and we need to put it in the required category
![Image](https://static.javatpoint.com/tutorial/machine-learning/images/k-nearest-neighbor-algorithm-for-machine-learning3.png)

Firstly, we will choose the number of neighbors, so we will choose the `k=5`.

The Euclidean distance is the distance between two points, which we have already studied in geometry. It can be calculated as:
![Image](https://static.javatpoint.com/tutorial/machine-learning/images/k-nearest-neighbor-algorithm-for-machine-learning4.png)

By calculating the Euclidean distance we got the nearest neighbors, as three nearest neighbors in category A and two nearest neighbors in category B. Consider the below image:

![Image](https://static.javatpoint.com/tutorial/machine-learning/images/k-nearest-neighbor-algorithm-for-machine-learning5.png)

As we can see, Category A have `3 neighbors` and category B have `2 neighbors`.

Hence, the new data point must belong to **category A**, because the number of the neighbor is maximum.

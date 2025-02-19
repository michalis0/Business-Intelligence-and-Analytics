# CLUSTERING 

This week, we are exploring various clustering algorithms from scikit-learn, which are particularly useful for understanding **unlabeled data**. Unlabeled data refers to the observations where we have certain features or metrics but lack predefined class labels. The main advantage of clustering is that it doesn't require prior knowledge of the number of classes or any labeled data. Instead, the algorithms identify the underlying structure within the data on their own.

<img src='https://static.javatpoint.com/tutorial/machine-learning/images/k-means-clustering-algorithm-in-machine-learning.png' width="300">

## STRUCTURE

Please have a look at the [walkthrough](walkthrough.ipynb) for an introduction to **two** clustering algorithms:
 - *KMeans*
 - *hierarchical clustering*.
We'll also see how to plot dendrograms, which show the hierachical relationship between observations.

You will then get a chance to practice with the help of the [exercises](exercises/exercise_clustering.ipynb).

## AT HOME

Try to solve on your own the [exercises for this week](exercises/exercise_clustering.ipynb).

**Note**: Clustering can be computation-intensive, which is why some cells in the exercise notebook take a bit of time to run. 
This is especially true for questions 2 (~2 mins) and 7 (~10 mins) of the exercise. 
While these cells run, you can simply assume that your code is correct (if no error message shows up in the first seconds) and look at the next questions. 
This means that you can fill the dots ( ... ) without running the cells while waiting for the other, computation-intensive, cell to display its full output.

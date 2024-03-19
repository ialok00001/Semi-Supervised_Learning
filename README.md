# Semi-Supervised Learning

Here, I have worked with two different datasets of MNIST - the Overhead MNIST and the Fashion MNIST. I aimed to use a clustering algorithm on each of the datasets and then use the centroids of these clusters as my only labels to train my classification models. This method is very useful in situations where the dataset is itself extremely big or getting a large number of labeled data is much more costly than getting the same amount of unlabelled data.

Choosing the right number of clusters is also a problem. Hence I have used visualization techniques and some of my reasoning to them to deduce the optimal number of clusters needed for both datasets. Also, I have used many classification models on these clustered points to compare their accuracies. In both the data, the SVM seemed to perform the best of all.

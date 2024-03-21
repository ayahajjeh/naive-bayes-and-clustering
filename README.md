# Naive Bayes Classification and Clustering
`This was one of my projects for the CS74 Machine Learning class at Dartmouth College.`

In the first part of this project, I built and trained a model to predict a label (either 0 or 1) based on 6 features for each data point using two methods: multinomial naive bayes with Laplace smoothing and gaussian naive bayes without smoothing. Then, I compared and evaluated the two models using macro F1 score and accuracy score.

In the second part of this project, I implemented the K-means clustering algorithm supporting two initialization methods: random split initialization and random seed selection. To evaluate and compare models with different hyperparameters such as number of clusters, initialization method, and max number of iterations, I implemented from scrath a function that calculates the silhouette score of each final clustering model.

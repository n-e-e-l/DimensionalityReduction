# DimensionalityReduction
Goal: To reduce the dimension of the data while retaining as much information as possible <br />
Data: https://www.kaggle.com/c/digit-recognizer


The given Data set has more than 800 columns.
### Principle component anlysis (PCA)

1.) Standardization<br />
2.) Covariance matrix computation<br />
3.) Compute the eigenvectors and eigenvalues of the covariance matrix to identify the principal components<br />
4.) Feature vector<br />
5.) Recast the data along the principal components axes<br />

![Alt text](https://github.com/n-e-e-l/DimensionalityReduction/blob/master/img/pca.png)

### T-Sne
1.) Compute probabilities proportional to the similarity of objects <br />
2.) Measure similarities between low-dimensional points <br />
3.) Minimization of the Kullback–Leibler divergence  reflects similarities between the high-dimensional inputs <br />

![Alt text](https://github.com/n-e-e-l/DimensionalityReduction/blob/master/img/T-sne.png)

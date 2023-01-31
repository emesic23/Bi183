# Problem 1
## A.
We can find the covariance matrix by $1/n X X^T$

## B.
To find the principle components, we calculate the covariance matrix as above, then we find the eigenvectors/values for the covariance matrix. Then, we take the eigenvectors that correspond to the largest eigenvalues, which are the principle components.

## C.
The principle components are the directions in the cell feature space that have the most variation in gene expression. The variance along the Principle component represents the variation in gene expression levels.

## D.
The maximum number of principle components with non-zero variance is the minimum of n and m. There are at most n non-zero eigenvalues. If n > m, then some of the variation is not captured by the principle components, which leads to a few zero eigenvalues.

# Problem 2
Data points:
(0,0)
(1,0)
(0,1)
(-1,0)
(0,-1)
(1,1)
(-1,-1)
(-1,1)

This gives us the covariance matrix of 1/8 * [4, 0][0, 4] with eigenvalues 4, with eigenvectors (1,0) and (0, 1)

# Problem 3
## A.
PCA removes all linear dependencies, but the relationships might be non-linear, which would not be captured and rmoved by PCA, so we do not capture these dependencies. 

## B.
if x is multivariate gaussian, PCA accomplishes statistical independence. Uncorrelated, jointly gaussian random variables are independent. PCA decorrelates the variables and transforms it via the eigenvectors found. Thus, we have transformed, uncorrelated variables, which are independent. 


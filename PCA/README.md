# Principal Components Analysis (PCA)

* What is it? => PCA is a popular technique to transform a dataset onto a lower dimensional subspace for visualization and data exploration. 
* When can we use it? Use to:
  * Select relevant variables
  * Identify which variables are related each to other 
* How does it work?=> transform data to new coordinates system (more variance).Linear transformation is stretching the plane in 2 directions given by the eigenvectors and eigenvalues. In other words, takes a lot of dimensions and reduce it to 2 o 3 dimensions so we can look it

# Application

* Background: In this example, we have 29 variables and the main purpose is to select the main principal components and identify the relationship among them.
* How to interpret the results?: 
  * Figure below present the 29 variables in two main componentes that explain 30.2% (x-axes) and 12.6% (y-axes) of the variances in the varibles
  * Greater the distance from center to variable means that this variable capture all the information of the pca
  * Variables that are cluster together means that there are highly correlated 


<img src="https://github.com/alminagorta/MyProjects/blob/master/PCA/PCA_1.png" width=280/>
<img src="https://github.com/alminagorta/MyProjects/blob/master/PCA/PCA_2.png" width=280/>

# Additional resources

* [Basic about PCA]

[Basic about PCA]: ftp://statgen.ncsu.edu/pub/thorne/molevoclass/AtchleyOct19.pdf


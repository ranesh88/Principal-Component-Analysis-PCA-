# Principle-Component-Analysis

## What Is Principal Component Analysis? 

Principal component analysis, or PCA, is a dimensionality reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.Principal component analysis, or PCA, is a statistical procedure that allows you to summarize the information content in large data tables by means of a smaller set of “summary indices” that can be more easily visualized and analyzed.

## What are the objectives of principal component analysis?

Data compression: PCA can be used to reduce the dimensionality of high-dimensional datasets, making them easier to store and analyze. Feature extraction: PCA can be used to identify the most important features in a dataset, which can be used to build predictive models.

## What are principal component analysis concepts?

Principal Component Analysis (PCA) is a statistical procedure that uses an orthogonal transformation that converts a set of correlated variables to a set of uncorrelated variables.PCA is the most widely used tool in exploratory data analysis and in machine learning for predictive models.

## What are the benefits of PCA?

Other benefits of PCA include reduction of noise in the data, feature selection (to a certain extent), and the ability to produce independent, uncorrelated features of the data. PCA also allows us to visualize data and allow for the inspection of clustering/classification algorithms.

## What is the formula for principal component analysis?

The k-th principal component of a data vector x(i) can therefore be given as a score tk(i) = x(i) ⋅ w(k) in the transformed coordinates, or as the corresponding vector in the space of the original variables, {x(i) ⋅ w(k)} w(k), where w(k) is the kth eigenvector of XTX.

## What are the components in principal component analysis?

Two major components are calculated in PCA: the first principal component (PC1) and the second principal component (PC2). The first principal component (PC1) is the direction in space along which the data points have the highest or most variance. It is the line that best represents the shape of the projected points

## Limitations of PCA

PCA is a powerful and versatile technique, but it also has some limitations that you should be aware of. For example, PCA is sensitive to the choice of variables and the order of observations, meaning that different selections or arrangements of your data may lead to different results. Therefore, you should always justify your choice of variables and ensure that your data is randomly ordered before applying PCA. Another limitation is that PCA is not robust to missing values, meaning that if your data has gaps or errors, PCA may not work properly or produce inaccurate results. Therefore, you should always handle missing values properly before applying PCA, such as by imputing them, deleting them, or using methods that can deal with them, such as probabilistic PCA or multiple imputation.



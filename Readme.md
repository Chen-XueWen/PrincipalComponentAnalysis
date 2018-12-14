# Principal Component Analysis (PCA)
## Introduction
PCA is usually used in facial recognition due to its ability to "detect" characteristics of the target (e.g face) as long as there are sufficient images for it to train with. In addition, the benefits of using PCA is dimensionality reduction by converting values (this case pixels) into vectors values that represent the principal axis. Principal axis is the vector that represents the many images and the axis with the most variance contains the most information. Hence the beauty of this algorithm is, it is able to convert a 32 x 32 (1024 values) into only 50 values for example if the top 50 eigenvalues are chosen. It will be clearer as we proceed.

## Process
1. First we get the mean of the dataset. The image below is the mean of all the cat images.
![Alt text](https://github.com/Chen-XueWen/PrincipalComponentAnalysis/blob/master/CatMean.png)


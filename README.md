# Cryptocurrencies

## Overview

The goal of this project was to determine investment opportunities in cryptocurrencies by using unsupervised machine learning to discover patterns in data. 

Using Jupyter, pandas, sklearn library, and hvPlot, I first preprocessed the data to prepare it for the unsupervised model, then used clustering and K-means algorithm to group data together, and then used principle component analysis (PCA) to limit the features and speed up the model to make it more efficient.  

## Results

An elbow curve was created with the K-means algorithm which helped determine the best value for K was 4. 

![Elbow_Curve](https://user-images.githubusercontent.com/90162669/151669007-a5c10fc7-a8f3-4c3c-a220-79507727d2a0.png)

Hvplot was used to visualize the data in 3d and 2d plots. 

![3d_scatter](https://user-images.githubusercontent.com/90162669/151669013-51823413-c6cc-4606-8e2f-684a8bb90c05.png)


![2d_plot](https://user-images.githubusercontent.com/90162669/151669017-4da8be8d-b30f-45f8-bb24-6fda2c26ebf4.png)


Unfortunately, the explained variance for this model is extremely low which indicates the results are not reliable. 

![explained_variance_ratio](https://user-images.githubusercontent.com/90162669/151668993-7b08ba01-0853-4e73-a3b7-d710a4f1d056.png)


## Summary
Because of the extremely low variance ratio, I do not recommend using this model to determine whether or not cryptocurrencies are a good investment or which specific cryptocurrencies would be a good investment. Further analysis is needed.  

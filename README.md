# Neural_Network_Charity_Analysis

Overview

In this analysis we had to use Machine learning and Neural networks to make predictions.  Using the dataset we had to create a binary classifier that would predict if the Alphabet Soup charity applicants funding will be successful.  

Results

In the first attempt the model has two hidden layers.  The first layer is 80 neurons, the second is 30.  

![Attempt 1](https://user-images.githubusercontent.com/92127589/155922014-1f0b0fcf-5b45-4abc-933b-224e93a98308.PNG)

The model reached 69%.  It did not reach 75%

![attempt 1 accuracy](https://user-images.githubusercontent.com/92127589/155922051-b4d81df2-469f-4f0a-a70b-450dd4b9578d.PNG)

In attempt 2 additional neurons were added and hidden layers were added

![Attempt 2](https://user-images.githubusercontent.com/92127589/155922091-556973e4-d07a-4351-ac59-8c63dfae6dc3.PNG)


The accuracy reached 53%

![Attempt 2 Accuracy](https://user-images.githubusercontent.com/92127589/155922113-34b81907-5272-4446-b980-b9f137bef123.PNG)


In attempt 3 the activation function of output layer from sigmoid to tanh


![Attempt 3](https://user-images.githubusercontent.com/92127589/155922141-3cd33f70-c9f1-4faf-83c3-08953bf78a0f.PNG)

The model reached 47% accuracy

![Attempt 3 accuracy](https://user-images.githubusercontent.com/92127589/155922150-379e7feb-011b-4973-a8ef-dcf9508c0ef0.PNG)


Summary

In the initial neural network accuracy had a score of 73%.  After the third attempt the model had a score of 47%.  A recommendation for how a different model could solve the classification problem is to use the random forest classifier.  I would recommend this because of its number of estimators and tree depth.  It also has faster performance than neural networks.  

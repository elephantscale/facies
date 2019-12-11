# Facies identification using Machine Learning

The goal is to perform facies identification with various types of Machine Learning.
  
We start with this projects (which occasionally appears to be offline).
but we introduced a new the new goal.

[Facies classification using machine learning](https://wiki.seg.org/wiki/Facies_classification_using_machine_learning)
 
Prediction usually works horizontally, level by level, but this approach does not
take the vertical extent of the data into account.

By contrast, ![this paper](doc/Blocking%20-%20A%20New%20Technique%20for%20Well%20Log%20Interpretation.pdf)
suggest corrections to log values based on vertical logic.

Our idea in this project is to combine both horizontal and vertical approaches. 
We will look at the logs as something that can be filtered, and this filter is similar to the
Convolutional Neural Network (CNN) approach. So that is our final goal. We will train
the neural network to optimize for formation tops!


Useful references:

[CNN in R (example)](https://www.r-bloggers.com/convolutional-neural-networks-in-r/)

Illustration of the problem

![Well](images/facies.jpeg)
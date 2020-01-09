# Udacity-Dog-Breed-Classifier
Udacity Deep Learning Nanodegree CNN Project

Original repo for this project can be found [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification).

## Objective
Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

## Results
- implemented human detector model

![](face-detector.png)

- implemented dog detector model

![](sample-dog-output.png)

- created a CNN to classify dog breeds (from scratch); after training the model for 15 epochs I achieved a test accuracy of 20% and a loss of 3.359957

![](sample_human_output.png)

- created a CNN using transfer learning (using VGG16 model), obtained an accuracy of 82% and reduced the loss to 0.5

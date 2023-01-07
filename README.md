# Vanilla_Gradient_Descent_on_MSE
Implement Gradient Descent on MSE from a Neural Network perspective


## Objective of this notebook
- To implement Gradient Decsent on MSE Loss function from a neural network perspective
- Details of the **problem statement**  , **data set** ,  **summary of the code/solution**  , **sample output/Prediction** from the program and **final result** of the project are listed in the sections to follow.

## Problem Statement/Prologue
Gradient Descent is where the magic happens and this optimization algorithm is used in many ML/DL algorithms such as Linear Regression, Logistic Regression , SVM & Neural Networks.We seldom have to implement this algorithm oursleves because the libraries implement it under the hood.

Inspite of being a fundamental concept in ML , this has always been a daunting concept , especially for beginners. Theortically it involves Calculus and Vector Algebra but how does it all pan out in terms of code ? Implementing the Gradient Descent algorithm helps one understand this algorithm at a granular level.

## Data Description:
The dataset is manually created for the purpose of this exercise

## Domain:
Deep Learning :Proof of concept

## Summary of the Solution/Code:
We will be finding the best fit line on the given data set using Gradient Decsent i.e we will be implementing gradient decsent on the MSE loss function.Below is the step wise breakdown of the code

- We will begin by manually creating a 2D data set & visualize the data set
- Note here that at this point , we already know what the best fit line for this data looks like.
- We will then implement Gradient Descent & see whether we can arrive at this best fit line through the gradient Descent algorithm
- We start at random point and and iteratvely keep reducing the loss until we arrive at the best fit line
- Cross vaidate whether the "best fit" line we arrived at through gradient decsnt is indeed the best fit line.
- We will realize all the operations in matrix format because we are implemting this from a neural network perspective
- Refer **python worksheet  Gradient_Descent_On_MSE.ipynb** for the solution

## Visualizing Input :

![image](https://user-images.githubusercontent.com/68383273/209479217-1954188c-72ff-49d5-b8b0-cd940459b1f0.png)


The above image depicts the following
- We start at a random line (marked in RED)
- The BLUE line indicates the best fit line which is our target
- We need to arrive at this line through the Gradient Descent Algorithm


## Intermediate Output :

![image](https://user-images.githubusercontent.com/68383273/209479268-2d0b4656-41ae-4884-a417-578393c2bd1f.png)

- The Green line in the above diagram indicates the line that was arrived at by the gradient descent algorithm after 1 iteration

## Final Output :

![image](https://user-images.githubusercontent.com/68383273/209479298-49cca43b-b162-4bea-9abb-b2b7c4052c17.png)
- Red line indicates the random line which we started at 
- The green lines indicate the line arrived at my the gradient descent algorithm at every iteration
- Note how the green line keeps moving towards the target line i.e blue line 
- Finally we see how the green line has almost overlapped with the target line demostarting how the gradient descent algorithm arrived at the best fit/target line through multiple iterations.

## Result :

![image](https://user-images.githubusercontent.com/68383273/211143706-0d2c6951-d70f-4d6e-8f72-dd21ebbb459e.png)


## References
The following references were used while creating this notebook:
- https://towardsdatascience.com/linear-regression-using-gradient-descent-97a6c8700931 by Adarsh Menon
- Post Graduation AI/ML Study Material by GL/UAT


# softmax-regression-from-scratch
Softmax regression using batch gradient descent and early stopping on the Iris dataset

Following Hands-On Machine Learning with Scikit-Learn and PyTorch Chapter 4 exercise 12

Dataset: Iris  

Features: petal length, petal width, sepal length, sepal width 

No Scikit-Learn model APIs used.

What I learned:
- bias term reasoning and implementation
- softmax formula and implementation
- one-hot encoding from scratch no numpy
- cross-entropy loss
- batch gradient descent used to minimize cross-entropy loss
- early stopping based on a patience counter
- validation/test accuracy by splitting and randomizing the sorted iris dataset

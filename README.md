# A Comprehensive Guide on Optimizers in Deep Learning

Mangesh Pawar

Introduction
Deep learning is the subfield of machine learning which is used to perform complex tasks such as speech recognition, text classification, etc. The deep learning model consists of an activation function, input, output, hidden layers, loss function, etc. All deep learning algorithms try to generalize the data using an algorithm and try to make predictions on unseen data. We need an algorithm that maps the examples of inputs to that of the outputs along with an optimization algorithm. An optimization algorithm finds the value of the parameters (weights) that minimize the error when mapping inputs to outputs. This article will tell you all about such optimization algorithms or optimizers in deep learning.
In this guide, we will learn about different optimizers used in building a deep learning model, their pros and cons, and the factors that could make you choose an optimizer instead of others for your application.
Learning Objectives
•	Understand the concept of deep learning and the role of optimizers in the training process.
•	Understand the mathematical principles behind optimizers, such as gradient descent and the learning rate.
•	Understand how to adjust optimizer parameters to optimize training performance and prevent overfitting.
Table of Contents
1.	What Are Optimizers in Deep Learning?
2.	Gradient Descent Deep Learning Optimizer
3.	Stochastic Gradient Descent Deep Learning Optimizer
4.	Stochastic Gradient Descent With Momentum Deep Learning Optimizer
5.	Mini Batch Gradient Descent Deep Learning Optimizer
6.	Adagrad (Adaptive Gradient Descent) Deep Learning Optimizer
7.	RMS Prop (Root Mean Square) Deep Learning Optimizer
8.	AdaDelta Deep Learning Optimizer
9.	Adam Deep Learning Optimizer
10.	Hands-on Optimizers
11.	Summary
12.	Conclusion

What Are Optimizers in Deep Learning?
As mentioned in the introduction, optimizer algorithms are a type of optimization method that helps improve a deep learning model’s performance. These optimization algorithms or optimizers widely affect the accuracy and speed training of the deep learning model. But first of all, the question arises of what an optimizer really is.
While training the deep learning optimizers model, we need to modify each epoch’s weights and minimize the loss function. An optimizer is a function or an algorithm that modifies the attributes of the neural network, such as weights and learning rates. Thus, it helps in reducing the overall loss and improving accuracy. The problem of choosing the right weights for the model is a daunting task, as a deep learning model generally consists of millions of parameters. It raises the need to choose a suitable optimization algorithm for your application. Hence understanding these machine learning algorithms is necessary for data scientists before having a deep dive into the field.
You can use different optimizers in the machine learning model to make changes in your weights and learning rate. However, choosing the best optimizer depends upon the application. As a beginner, one evil thought that comes to mind is that we try all the possibilities and choose the one that shows the best results. This might not be a problem initially, but when dealing with hundreds of gigabytes of data, even a single epoch can take a considerable amount of time. So randomly choosing an algorithm is no less than gambling with your precious time that you will realize sooner or later in your journey.
This guide will cover various deep-learning optimizers, such as Gradient Descent, Stochastic Gradient Descent, Stochastic Gradient descent with momentum, Mini-Batch Gradient Descent, Adagrad, RMSProp, AdaDelta, and Adam. So, by the end of the article, you will be able to compare various optimizers and the procedure they are based upon.


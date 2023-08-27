# Neural-Network-Regression-using-Tensorflow

# Linear Regression

Linear Regression is a supervised learning technique that involves learning the relationship between the features and the target. The target values are continuous, which means that the values can take any values between an interval. For example, 1.2, 2.4, and 5.6 are considered to be continuous values. Use-cases of regression include stock market price prediction, house price prediction, sales prediction, and etc.

![376451__TqRJ9SmwFzRigJhMiN2uw](https://github.com/HiteshRam666/Neural-Network-Regression-using-Tensorflow/assets/116026459/10a59667-289a-45d1-b180-cbe9ee767a1a)



The y hat is called the hypothesis function. The objective of linear regression is to learn the parameters in the hypothesis function. The model parameters are, intercept (beta 0) and the slope (beta 1). The above equation is valid for univariate data, which means there is only one column in the data as a feature.

How does linear regression learn the parameters?

<img width="453" alt="81628Screen Shot 2021-08-14 at 3 57 42 PM" src="https://github.com/HiteshRam666/Neural-Network-Regression-using-Tensorflow/assets/116026459/b2bc90ba-599c-43b3-9db5-63097207853f">


The numerator denotes the covariance of the data and the denominator denotes the variance of the feature X. The result will be the value of beta 1 which is also called the slope. The beta 1 parameter determines the slope of the linear regression line. The intercept decides where the line should pass through in the y-axis.

![76314400px-Linear_regression svg](https://github.com/HiteshRam666/Neural-Network-Regression-using-Tensorflow/assets/116026459/137bf741-c618-4cde-b30e-1f4bcfde4882)


## Regression using Artificial Neural Networks

### Why do we need to use Artificial Neural Networks for Regression instead of simply using Linear Regression?

The purpose of using Artificial Neural Networks for Regression over Linear Regression is that the linear regression can only learn the linear relationship between the features and target and therefore cannot learn the complex non-linear relationship. In order to learn the complex non-linear relationship between the features and target, we are in need of other techniques. One of those techniques is to use Artificial Neural Networks. Artificial Neural Networks have the ability to learn the complex relationship between the features and target due to the presence of activation function in each layer. Let’s look at what are Artificial Neural Networks and how do they work.

## Artificial Neural Networks

Artificial Neural Networks are one of the deep learning algorithms that simulate the workings of neurons in the human brain. There are many types of Artificial Neural Networks, Vanilla Neural Networks, Recurrent Neural Networks, and Convolutional Neural Networks. The Vanilla Neural Networks have the ability to handle structured data only, whereas the Recurrent Neural Networks and Convolutional Neural Networks have the ability to handle unstructured data very well. In this post, we are going to use Vanilla Neural Networks to perform the Regression Analysis.

### Structure of Artificial Neural Networks

![44122Architecture-of-multilayer-artificial-neural-network-with-error-backpropagation](https://github.com/HiteshRam666/Neural-Network-Regression-using-Tensorflow/assets/116026459/db9d0068-cb26-497c-8943-8303f19217f3)


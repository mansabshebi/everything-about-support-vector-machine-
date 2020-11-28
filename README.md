# everything-about-support-vector-machine-
Most of the tasks machine learning handles right now include things like classifying images, translating languages, handling large amounts of data from sensors, and predicting future values based on current values. You can choose different strategies to fit the problem you're trying to solve.

The good news? There's an algorithm in machine learning that'll handle just about any data you can throw at it. But we'll get there in a minute.

Supervised vs Unsupervised learning
Two of the most commonly used strategies in machine learning include supervised learning and unsupervised learning.

What is supervised learning?
Supervised learning is when you train a machine learning model using labelled data. It means that you have data that already have the right classification associated with them. One common use of supervised learning is to help you predict values for new data.

With supervised learning, you'll need to rebuild your models as you get new data to make sure that the predictions returned are still accurate. An example of supervised learning would be labeling pictures of food. You could have a dataset dedicated to just images of pizza to teach your model what pizza is.

What is unsupervised learning?
Unsupervised learning is when you train a model with unlabeled data. This means that the model will have to find its own features and make predictions based on how it classifies the data.

An example of unsupervised learning would be giving your model pictures of multiple kinds of food with no labels. The dataset would have images of pizza, fries, and other foods and you could use different algorithms to get the model to identify just the images of pizza without any labels.

So what's an algorithm?
When you hear people talk about machine learning algorithms, remember that they are talking about different math equations.

An algorithm is just a customizable math function. That's why most algorithms have things like cost functions, weight values, and parameter functions that you can interchange based on the data you're working with. At its core, machine learning is just a bunch of math equations that need to be solved really fast.

That's why there are so many different algorithms to handle different kinds of data. One particular algorithm is the support vector machine (SVM) and that's what this article is going to cover in detail.

What is an SVM?
Support vector machines are a set of supervised learning methods used for classification, regression, and outliers detection. All of these are common tasks in machine learning.

You can use them to detect cancerous cells based on millions of images or you can use them to predict future driving routes with a well-fitted regression model.

There are specific types of SVMs you can use for particular machine learning problems, like support vector regression (SVR) which is an extension of support vector classification (SVC).

The main thing to keep in mind here is that these are just math equations tuned to give you the most accurate answer possible as quickly as possible.

SVMs are different from other classification algorithms because of the way they choose the decision boundary that maximizes the distance from the nearest data points of all the classes. The decision boundary created by SVMs is called the maximum margin classifier or the maximum margin hyper plane.

How an SVM works
A simple linear SVM classifier works by making a straight line between two classes. That means all of the data points on one side of the line will represent a category and the data points on the other side of the line will be put into a different category. This means there can be an infinite number of lines to choose from.

What makes the linear SVM algorithm better than some of the other algorithms, like k-nearest neighbors, is that it chooses the best line to classify your data points. It chooses the line that separates the data and is the furthest away from the closet data points as possible.

A 2-D example helps to make sense of all the machine learning jargon. Basically you have some data points on a grid. You're trying to separate these data points by the category they should fit in, but you don't want to have any data in the wrong category. That means you're trying to find the line between the two closest points that keeps the other data points separated.

So the two closest data points give you the support vectors you'll use to find that line. That line is called the decision boundary.


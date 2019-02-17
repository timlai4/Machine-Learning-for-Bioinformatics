In the next few weeks we will talk about some machine learning algorithms and their application. We will not be implimenting these algorithms but will be using packages that allready implemented the. The main package we will be using is [scikit-learn](http://scikit-learn.org/). This is the most widely used machine learning package for python. There are so many excellent tutorials on scikit-learn, in these next few labs we are going to practive some tutorials and uses of this ML algorithms by first understanding how they work and testing them over different types of datasets. I will be emphasizing important points through experience. 

We will start with the [scikit-learn basic tutorial](http://scikit-learn.org/stable/tutorial/basic/tutorial.html).
Scikit-learn is famous for its excellent documentation which is also a great resource for machine learning in general.
This simple tutorial walks us through the organization of scikit-learn and introduces the generic methods `fit()` and `predict()` implemented for various classifiers.

We will start with the [scikit-learn basic tutorial](http://scikit-learn.org/stable/tutorial/basic/tutorial.html).
Scikit-learn is famous for its excellent documentation which is also a great resource for machine learning in general.
This simple tutorial walks us through the organization of scikit-learn and introduces the generic methods `fit()` and `predict()` implemented for various classifiers.

Generally speaking, a learning problem considers a set of n samples of data and then tries to predict properties of unknown data. If each sample is more than a single number and, for instance, a multi-dimensional entry (aka multivariate data), it is said to have several attributes or features. As you might have heard before machine learning is generally split between unsupervised learning and supervised learning. Although there are also semi-supervised learning approaches, and reinforcement learning methods, however in this class we will focus only on supervised and unsupervised methods. We have allready seen some unsupervised methods such as our clustering algorithms (k-means, hierarchical clustering etc...). So whats the difference between supvervised and unsupervised?:

* supervised learning, in which the data comes with additional attributes that we want to predict (Click here to go to the scikit-learn supervised learning page).This problem can be either:

   * classification: samples belong to two or more classes and we want to learn from already labeled data how to predict the class of unlabeled data. An example of a classification problem would be handwritten digit recognition, in which the aim is to assign each input vector to one of a finite number of discrete categories. Another way to think of classification is as a discrete (as opposed to continuous) form of supervised learning where one has a limited number of categories and for each of the n samples provided, one is to try to label them with the correct category or class.
regression: if the desired output consists of one or more continuous variables, then the task is called regression. An example of a regression problem would be the prediction of the length of a salmon as a function of its age and weight.
unsupervised learning, in which the training data consists of a set of input vectors x without any corresponding target values. The goal in such problems may be to discover groups of similar examples within the data, where it is called clustering, or to determine the distribution of data within the input space, known as density estimation, or to project the data from a high-dimensional space down to two or three dimensions for the purpose of visualization (Click here to go to the Scikit-Learn unsupervised learning page).

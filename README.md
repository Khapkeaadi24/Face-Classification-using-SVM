What is Support Vector Machines?

SVMs are a powerful class of supervised learning algorithms for classification and regression problems. In the context of classification, SVMs can be viewed as maximum margin linear classifiers.

The SVM uses an objective which explicitly encourages low out-of-sample error (good generalization performance). The D dimensional data are divided into classes by maximizing the margin between the hyperplanes for the classes.

Note that we assume the two classes in the data are linearly separable. Later, for non-linear boundaries, we will use the kernel trick to exploit higher (possibly infinite) dimensional 
-spaces, where the classes are linearly separable, find the support vectors in this space and map it back to the dimensionality of our problem

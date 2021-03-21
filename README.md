# ML_Intro_Notebooks

This is a series of notebooks that mark my progress in reading and practicing the concepts presented by Muller and Guido in the book Introduction to Machine Learning with Python: A Guide for Data Scientists.

Chapter 1: Basic ML concepts and the first example with Iris dataset and KNN Classifier.

Chapter 2: Overview of a bunch of ML algorithms.

	Nearest Neighbors
		- Easy to explain
		- Good as baseline
		- Not good for large and high dimensional datasets
		- non-linear time complexity

	Linear Models
		- Good for large and high dimensional sparse datasets
		- Usually fast
		- Easy to explain
		- Some can perform feature selection
		- Sensible to scaling
		- Sensible to parameter tuning
		- Models are limited to hyperplanes

	Naive Bayes
		- Very very fast
		- Only for classification
		- Good for large and high dimensional datasets
		- Often less accurate than Linear Models 

	Decision Trees
		- Very fast
		- Robust to scaling
		- Very very easy to explain

	Random Forests
		- Better than a Decision Tree alone
		- Very robust and powerful
		- Robust to scalin
		- Not very good to high-dimensional sparse data

	Gradient Boosted Decision Trees
		- Often better than Random Forests
		- Slower to train tran Random Forests, but faster to predict and smaller in memory
		- Often needs parameter tuning

	Support Vector Machines
		- Poweful for medium-size datasets
		- Requires scaling
		- Very sensitive to parameter tuning

	Neural Networks
		- Can build very complex models
		- Sensitive to scaling of the data
		- Sensitive to parameter tuning
		- Long time to train

Chapter 3: Unsupervised Learning and Preprocessing
	
	Scaling
		- StandardScaler
		- RobustScaler
		- MinMaxScaler
		- Normalizer
	
	Dimensionality Reduction, Feature Extraction and Manifold Learning 
		- Principal Component Analysis (PCA)
		- Non-Negative Matrix Factorization
		- Manifold Learning with t-SNE
	
	Clustering
		- *k*-Means Clustering
		- Agglomerative Clustering
		- DBSCAN
	
	Clustering Evaluation
		- Adjusted Rand Index (ARI)
		- Normalized Mutual Information (NMI)
		- Sillhouette Coefficient
		- Robustness-based clustering metrics
		- Qualitative Method
	

Chapter 4: Representing Data and Engineering Features
Chapter 5: Model Evaluation and Improvement

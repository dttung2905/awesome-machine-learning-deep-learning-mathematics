# awesome machine learning and deep learning mathematics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome machine learning and deep learning mathematics and advanced mathematics descriptions,documents,concepts,study materials,videos,libraries and software (by language).

[![Main Architecture 1](https://image.slidesharecdn.com/machinelearningwithapachemahout-120216160514-phpapp02/95/machine-learning-with-apache-mahout-15-728.jpg?cb=1329409119)](https://ocw.mit.edu/courses/mathematics/18-657-mathematics-of-machine-learning-fall-2015/)
[![Main Architecture 2](https://whatsthebigdata.files.wordpress.com/2017/03/machinelearning_mathtopics.png?w=640)](https://ocw.mit.edu/courses/mathematics/18-657-mathematics-of-machine-learning-fall-2015/)                        

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [INTRODUCTION](#introduction)
    - [Why Maths Important for Machine Learning?](#introduction-why-maths)
- [BASICS](#basics)
    - [What is Machine Learning?](#basics-what-machinelearning)
    - [What is Deep Learning?](#basics-what-deeplearning)
    - [Applications of Mathematics in Machine and Deep Learning?](#basics-what-topological-quantum-computing)
    - [Machine and Deep Learning with Mathematics vs without Mathematics](#basics-mathematics-nonmathematics-vs) 
- [MATHEMATICAL TOPICS FOR MACHINE AND DEEP LEARNING](#mathematicaltopics)
    - [Linear Algebra](#mathematicaltopics-linear-algebra)
    - [Probability and Statistics](#mathematicaltopics-probability-statistics)
    - [Linear Calculus](#mathematicaltopics-linear-calculus)
    - [Vector Calculus](#mathematicaltopics-vector-calculus)
    - [Tensor Calculus](#mathematicaltopics-tensor-calculus)
    - [Graphs Theory](#mathematicaltopics-graphs-theory)
    - [Complexity Theorems](#mathematicaltopics-complexity-theorems)
    - [Number Theory](#mathematicaltopics-number-theory)
    - [Optimization Theorems](#mathematicaltopics-optimizationtheorems)
- [LINEAR ALGEBRA](#mathematicallinearalgebra)
    - [Linear Equations](#mathematicallinearalgebra-linearequations)
    - [Polynomial Equations](#mathematicallinearalgebra-polynomialequations)
    - [Vectors](#mathematicallinearalgebra-vectors)             
    - [Matrices](#mathematicallinearalgebra-matrices)
    - [Tensors](#mathematicallinearalgebra-tensors)
    - [Vector Space](#mathematicallinearalgebra-vectorspace)
    - [eigenvalues and eigenvectors](#mathematicallinearalgebra-eigen)
    - [Cartesian Coordinate System](#mathematicallinearalgebra-cartesian)
    - [Matrix Decomposition](#mathematicallinearalgebra-matrixdecomposition)
    - [Tensor Decomposition](#mathematicallinearalgebra-tensordecomposition)
    - [Structural Geometry](#mathematicallinearalgebra-structural-geometry)
- [PROBABILITY AND STATISTICS](#mathematicalprobabilitystatistics)
    - [Probability](#mathematicalprobabilitystatistics-probability)
    - [Rules of probability](#mathematicalprobabilitystatistics-rulesprobability)
    - [Mean](#mathematicalprobabilitystatistics-mean)
    - [Median](#mathematicalprobabilitystatistics-median)
    - [Mode](#mathematicalprobabilitystatistics-mode)                 
    - [Variance](#mathematicalprobabilitystatistics-variance)
    - [Standard Deviation](#mathematicalprobabilitystatistics-standarddeviation)
    - [Random Variables](#mathematicalprobabilitystatistics-randomvariables)
    - [Probability Distribution](#mathematicalprobabilitystatistics-probabilitydistribution)
    - [Conditional Probability](#mathematicalprobabilitystatistics-conditionalprobability)
    - [Probability Density Function](#mathematicalprobabilitystatistics-probabilitydensityfunction)
    - [Cumulative Probability Distribution](#mathematicalprobabilitystatistics-cumulativeprobabilitydistribution)
    - [Sample or Sampling](#mathematicalprobabilitystatistics-sampling)
    - [Population](#mathematicalprobabilitystatistics-population)
    - [Statistical Inference](#mathematicalprobabilitystatistics-statisticalinference)
    - [Maximum likelihood](#mathematicalprobabilitystatistics-maximumlikelihood)
    - [Binomial Distribution](#mathematicalprobabilitystatistics-binomial)
    - [Normal Distribution](#mathematicalprobabilitystatistics-normal)
    - [Gaussian Distribution](#mathematicalprobabilitystatistics-gaussian)
    - [Statistical Models](#mathematicalprobabilitystatistics-statisticalmodels)
    - [Expectation Maximization](#mathematicalprobabilitystatistics-expectationmaximization)
    - [Central Limit Theorem](#mathematicalprobabilitystatistics-centrallimittheorem)
    - [Regression](#mathematicalprobabilitystatistics-regression)
    - [Linear Regression](#mathematicalprobabilitystatistics-linearregression)
    - [Stochastic Process](#mathematicalprobabilitystatistics-stochasticprocess)
    - [Hypothesis](#mathematicalprobabilitystatistics-hypothesis)
    - [Bayesian Probability](#mathematicalprobabilitystatistics-bayesian)
    - [Null Hypothesis](#mathematicalprobabilitystatistics-nullhypothesis)
    - [Confidence Interval](#mathematicalprobabilitystatistics-confidenceinterval)
    - [Correlation](#mathematicalprobabilitystatistics-correlation)
    - [Correlation Coefficient](#mathematicalprobabilitystatistics-correlationcoefficient)
    - [Histogram](#mathematicalprobabilitystatistics-histogram)
    - [Z-Score](#mathematicalprobabilitystatistics-zscore)
    - [Covariance](#mathematicalprobabilitystatistics-covariance)
    - [Least Square Fitting](#mathematicalprobabilitystatistics-leastsquarefitting)
    - [Posterior Probability](#mathematicalprobabilitystatistics-posteriorprobability)
    - [Bootstrapping](#mathematicalprobabilitystatistics-bootstrapping)
    - [Cross Validation](#mathematicalprobabilitystatistics-crossvalidation)
    - [Muller Theorem](#mathematicalprobabilitystatistics-mullertheorem)
- [MEETUPS](#mathematicalmeetups)
- [GOOGLE GROUPS](#mathematicalgroups)
- [COMPANIES DOING PRODUCTS](#mathematicalcompanies)
- [LINKEDLIN GROUPS](#mathematicallinkedlin)
- [DEGREES](#mathematicaldegrees)
- [CONSOLIDATED BOOKS](#mathematicalconsolidatedbooks)
- [CONSOLIDATED VIDEOS](#mathematicalconsolidatedvideos)
- [CONSOLIDATED Reserach Papers](#mathematicalconsolidatedresearchpapers)
- [CONSOLIDATED Reserach Scientist](#mathematicalconsolidatedresearchscientist)
                                                                   

<!-- /MarkdownTOC -->

### License

[![License](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/LICENCE)

### Dedicated Opensources

[![Dedicated Opensources](http://livingintown.com/wp-content/uploads/sites/1112/2015/03/coming-soon-small.jpg)]()
                                                                  
* Source code of plenty of Algortihms in Image Processing , Data Mining ,etc in Matlab, Python ,Java and VC++ Scripts
* Good Explanations of Plenty of algorithms with flow chart etc
* Comparison Matrix of plenty of algorithms

### Contribution

<a href="https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/contribution.md"><img src="http://comps.canstockphoto.com/can-stock-photo_csp23653568.jpg" align="left" height="200" width="200"></a>

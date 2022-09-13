---
title: "Missing Data and the Expectation Maximization (EM) Algorithm"
excerpt: "Group project for a Big Data & High Performance Statistical Computing course <br/><img src='/images/convergence.png'>"
collection: portfolio
---

ABSTRACT: The aim of this project is to research the Expectation-Maximization algorithm and learn how it can be used to estimate the maximum likelihood estimate (MLE) of unknown parameters in a statistical model when the data contains missing values. The approach iterates through the estimation (E) step, which computes a function for a lower bound of the likelihood of the observed data, and is followed by the maximization (M) step, which maximizes that lower bound. model parameters. We implement the EM algorithm from scratch. A simulation study shows that the EM algorithm is able to the estimate the unknown parameters, but doesn't perform well when clusters of data are overlapping. Then, we show that the EM algorithm had an accuracy of 99.6% on the "Mouse" dataset, which is a two-dimensional with 490 observations and three gaussian clusters. Lastly, we show that the results and run-time of our EM algorithm from scratch was similar to that of the built-in function *GaussianMixture* from *sklearn.mixture*.

[Download project here](http://daryapetrov.github.io/files/STA141C.pdf)

<iframe src="/files/STA141C.pdf" width="100%" height="600px">
</iframe>
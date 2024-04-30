# Non-Parametric-Prediction-Inteervals

This repository contains a small project exploring the the ability of the EnbPI algorithm presented in Chen Xu's and Yao Xie's article "Conformal Prediction Interval for Dynamic Time-Series". As the name suggests, it produces sequantial prediction intervals for time series with a given required coverage rate of the target varialbe. Theoretical work presented in the article shows its ability to give (under some assumptions) an approximate marginal coverage level. The beautiful thing about the algorithm is that, in the spirit of conformal prediction, it does not assume anything on the distribution of the data 

The attached R Markdown file contains my own code which takes the appropriate parameters for the algorithm, a time series as a training set, and returns prediction intervals for the points on a given test set.
This allows me to explore how the different parameters of the algorithm will effect its performance (coverage rate and the intervals' lengths).

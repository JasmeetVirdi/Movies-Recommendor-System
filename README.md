# Movies-Recommendor-System
--> run Anomaly.m to run this script on your octave terminal to implement an anomaly detection algorithm to detect
anomalous behavior in server computers.The features measure the through- put (mb/s) and latency (ms) of response of each server. While your servers were operating, you collected m = 307 examples of how they were behaving, and thus have an unlabeled dataset {x (1) , . . . , x (m) }. You suspect that the vast majority of these examples are “normal” (non-anomalous) examples of the servers operating normally, but there might also be some examples of servers acting anomalously within this dataset.
--> run Anomaly.m to run this script on your octave terminal to implement the collaborative filtering
learning algorithm and apply it to a dataset of movie ratings.This dataset consists of ratings on a scale of 1 to 5. The dataset has n(u) = 943 users, and n(m) = 1682 movies.

Anomaly.m - Octave/MATLAB script that steps you through the exercise Part 1
recommendor.m - Octave/MATLAB script that steps you through the exercise Part 2
sigmoidGradient.m	- Compute the gradient of the sigmoid function
randInitializeWeights.m	- Randomly initialize weights
nnCostFunction.m	- Neural network cost function
ex8data1.mat - First example Dataset for anomaly detection
ex8data2.mat - Second example Dataset for anomaly detection
ex8 movies.mat - Movie Review Dataset
ex8 movieParams.mat - Parameters provided for debugging
multivariateGaussian.m - Computes the probability density function
for a Gaussian distribution
visualizeFit.m - 2D plot of a Gaussian distribution and a dataset
checkCostFunction.m - Gradient checking for collaborative filtering
computeNumericalGradient.m - Numerically compute gradients
fmincg.m - Function minimization routine (similar to fminunc)
loadMovieList.m - Loads the list of movies into a cell-array
movie ids.txt - List of movies
normalizeRatings.m - Mean normalization for collaborative filtering
[ ] estimateGaussian.m - Estimate the parameters of a Gaussian dis-
tribution with a diagonal covariance matrix
[ ] selectThreshold.m - Find a threshold for anomaly detection
[ ] cofiCostFunc.m - Implement the cost function for collaborative fil-
tering


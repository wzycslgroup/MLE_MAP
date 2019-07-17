# MLE_MAP

## Overview

* The relaitionship between Joint probability and marginal probability
* How to use MLE estimate the parameters of the model?
* How to use MAP estimate the parameters of the model?
* What is the conjugate distribution of the binomial distribution? 
* What is the conjugate distribution of the category distribution?
* Under What condition, MLE can perform well? how about MAP?
* Under What condition, MLE can perform really bad? how about MAP?
* What's the relationship between MLE and MAP? In other words, under what conditions, MAP can be converted into MLE?


## Main Points

*  Joint probability distributions lie at the core of probabilistic machine learning approaches. Given the joint probability distribution over a
set of random variables, it is possible in principle to compute any joint or
conditional probability defined over any subset of these variables.

* Learning, or estimating, the joint probability distribution from training data can be easy if the data set is large compared to the number of distinct probability terms we must estimate. But in many practical problems the data
is more sparse, requiring methods that rely on prior knowledge or assumptions, in addition to observed data.

*  Maximum likelihood estimation (MLE) is one of two widely used principles
for estimating the parameters that define a probability distribution. This
principle is to choose the set of parameter values <a href="https://www.codecogs.com/eqnedit.php?latex=\hat{\theta}^{MLE}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\hat{\theta}^{MLE}" title="\hat{\theta}^{MLE}" /></a> that makes the observed training data most probable (over all the possible choices of θ):

<center><a href="https://www.codecogs.com/eqnedit.php?latex=\hat{\theta&space;}&space;{}^{MLE}&space;=&space;arg&space;\underset{\theta&space;}{max}&space;P(data\mid&space;\theta&space;)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\hat{\theta&space;}&space;{}^{MLE}&space;=&space;arg&space;\underset{\theta&space;}{max}&space;P(data\mid&space;\theta&space;)" title="\hat{\theta } {}^{MLE} = arg \underset{\theta }{max} P(data\mid \theta )" /></a></center>

*  Maximium a posteriori probability (MAP) estimation is the other of the two
widely used principles. This principle is to choose the most probable value
of θ, given the observed training data plus a prior probability distribution
P(θ) which captures prior knowledge or assumptions about the value of θ:

<center><a href="https://www.codecogs.com/eqnedit.php?latex=\hat{\theta}^{MAP}&space;=&space;arg&space;\underset{\theta&space;}{max}&space;P(data\mid\theta)P(\theta)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\hat{\theta}^{MAP}&space;=&space;arg&space;\underset{\theta&space;}{max}&space;P(data\mid\theta)P(\theta)" title="\hat{\theta}^{MAP} = arg \underset{\theta }{max} P(data\mid\theta)P(\theta)" /></a></center>

## Resources

### CMU 10-601

#### Readings 

* [Estimating Probabilities: MLE and MAP. Tom Mitchell (2016, draft)](http://www.cs.cmu.edu/~tom/mlbook/Joint_MLE_MAP.pdf)  

#### Slides

* [MLE&MAP(CMU 10-601)](http://www.cs.cmu.edu/~mgormley/courses/10601-s18/slides/lecture20-mle-map.pdf)

### Cornell CS4780

#### Leacture notes

* [Estimating from the data](http://www.cs.cornell.edu/courses/cs4780/2018fa/lectures/lecturenote04.html)

#### Videos

* [Estimating from the data](https://www.youtube.com/watch?v=RIawrYLVdIw&index=7&list=PLl8OlHZGYOQ7bkVbuRthEsaLr7bONzbXS)


# Probability Distributions Package

A `probability distribution` is a function that describes the likelihood of obtaining the possible values that a random variable can assume. 
This python package `udmlprob_distributions` defines functions for calculating and visualizing `Gaussian` and `Binomial distributions`. The Gaussian distribution is a continuous probability distribution for a real-valued random variable, and it is known as the standard normal distribution in its simplest form with a mean of zero and standard deviation of 1. On the  other hand, Binomial Distribution is the discrete probability distribution of the number of successes in a sequence of _n_ independent experiments, each asking a _yes–no_ question, and each with its own boolean-valued outcome: _success/yes/true/one_ (with probability _p_) or _failure/no/false/zero_ (with probability _q = 1 − p_).


# Files

There are three python files in this package for calculating and visualizing the probability density functions for the Gaussian and Binomial distributions of a random variable. These files are as follows:

* **Generaldistribution.py** - contains a generic distribution class for calculating and visualizing a probability distribution, with a function to read in a text data.
* **Gaussiandistribution.py** - contains a Gaussian distribution class, with functions to calculate the mean and standard deviation of a Gaussian distribution. Within this file are functions to visualize the instance variable data and the probability density function of the Gaussian distribution, add two Gaussian distributions and output the characteristics of the Gaussian instance.
* **Binomialdistribution.py** - contains a Binomial distribution class, with functions to calculate the mean and standard deviation of a Binomial distribution. Within this file are functions to visualize the instance variable data and the probability density function of the Binomial distribution, add two Binomial distributions, output the characteristics of the Binomial instance and calculate the probability and number of trials in the data.



# Installation
`udmlprob_distributions` can be installed via pip from [PyPI]('https://pypi.org/project/pandas').

pip install udmlprob_distributions


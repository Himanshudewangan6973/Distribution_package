# Udacity---AWS-Course
Gaussian and Binomial distributions - "stat-prob-distributions 0.1" package

# prob_distributions_package
	
- Binomial
- Gaussian(Normal)
    
# Files

- Binomialdistributions.py  : Binomial distribution class for calculating and 
    visualizing a Binomial distribution.
- Gaussiandistributions.py  : Gaussian distribution class for calculating and 
	visualizing a Gaussian distribution.
- Generaldistributions.py  : Generic distribution class for calculating and 
		visualizing a probability distribution.
- __init__.py  : Group all files :- by creating shortcuts

# Installation

    ```
    pip install stat-prob-distributions
    ```
    or
    ```
    pip install -i https://test.pypi.org/simple/ stat-prob-distributions
    ```
    
    ## Usage
    	```
	from stat_prob_distribution import Gaussian, Binomial
         - Gaussian(a, b)
         - Binomial(.a, b)
	```
    
# Attributes:

- mean (float) representing the mean value of the distribution
- stdev (float) representing the standard deviation of the distribution
- data_list (list of floats) a list of floats to be extracted from the data file
- p (float) representing the probability of an event occurring
- n (int) number of trials

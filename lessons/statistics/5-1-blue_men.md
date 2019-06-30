[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

import scipy.stats


mu = 178
sigma = 7.7
dist = scipy.stats.norm(loc=mu, scale=sigma)
type(dist)


low = dist.cdf(177.8)    # 5 foot 10

high = dist.cdf(185.4)   # 6 foot 1

print (low, high, high-low)

# 0.48963902786483265 0.8317337108107857 0.3420946829459531

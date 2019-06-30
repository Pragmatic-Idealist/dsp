[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

import sys
import numpy as np
import thinkstats2
import thinkplot
import matplotlib


#generate random numbers
n = np.random.random(1000)


#create random number pdf

pmf = thinkstats2.Pmf(n)
thinkplot.Pmf(pmf, linewidth= 1) 

thinkplot.Config(xlabel='Random Variables', ylabel='PMF')

#plot description: looks like a rectangular blob, appears to be relatively random as its uniformly distrubuted.


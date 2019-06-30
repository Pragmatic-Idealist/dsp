[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)


#generate random numbers
n = np.random.random(1000)


#create random number pdf
pmf = thinkstats2.Pmf(n)
thinkplot.Pmf(pmf, linewidth= 1) 
thinkplot.Config(xlabel='Random variate', ylabel='PMF')

#plot description: looks like a rectangular blob


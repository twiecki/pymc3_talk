Bayesian Data Analysis with PyMC3
=================================

Abstract
--------

Probabilistic Programming allows flexible specification of statistical models to gain insight from data. Estimation of best fitting parameter values, as well as uncertainty in these estimations, can be automated by sampling algorithms like Markov chain Monte Carlo (MCMC). The high interpretability and flexibility of this approach has lead to a huge paradigm shift in scientific fields ranging from Cognitive Science to Data Science and Quantitative Finance.

PyMC3 is a new Python module that features next generation sampling algorithms and an intuitive model specification syntax. The whole code base is written in pure Python and Just-in-time compiled via Theano for speed.

In this talk I will provide an intuitive introduction to Bayesian statistics and how probabilistic models can be specified and estimated using PyMC3.

Links
-----

* [Video of the talk at EuroPython](https://www.youtube.com/watch?v=WESld11iNcQ)
* [The reveal slide show EuroPython version](http://twiecki.github.io/bayesian_pymc3_europy_ab.slides.html#/)
* [Video of the talk at PyData](https://vimeo.com/79518830)
* [The reveal slide show PyData version](https://rawgithub.com/twiecki/pymc3_talk/master/bayesian_pymc3.slides.html)
* [PyMC repo](https://github.com/pymc-devs/pymc)

Presentations
-------------

There are two different talks on the same topic (EuroPython and PyData):
* [EuroPython 2014 conference Berlin](https://ep2014.europython.eu/en/schedule/sessions/80/) on Jul 24 2014 (different material)
* [PyData conference NYC](https://vimeo.com/79518830) on Nov 9 2013
* [Data Mining Meet-up](http://www.meetup.com/Boston-Data-Mining/events/144148692/) in Boston on Oct 15 2013 

Dependencies
------------

Depending on what you already installed, you may need to take the
following steps:

1. On OS X, you may need to install MacTex from
   http://mirror.ctan.org/systems/mac/mactex/MacTeX.pkg
   
2. pip install brewer2mpl
   brew install git
   pip install git+https://github.com/olgabot/prettyplotlib.git

3. pip install git+https://github.com/pymc-devs/pymc

4. pip install patsy
   pip install statsmodels

5. pip install zipline

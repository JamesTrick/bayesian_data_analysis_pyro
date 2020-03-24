# Bayesian Data Analysis with Pyro

<img align="right" style="padding-left: 10px" height="200px" src="http://www.stat.columbia.edu/~gelman/book/bda_cover.png">


This repository walks through [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/) by Gelman, Carlin, Stern, Dunson, Vehtari, and Rubin. Original code from the book is written in R, Python using Stan, and Matlab and is available on the book's website.

Bayesian Data Analysis is a great and highly recommended reading on Bayesian Methods. As such, this repository isn't designed to replace the learnings from the book, instead it'll hopefully teach you and give you confidence writing models in Pyro.

## Introduction Pyro

<img align="left" height="100" style="padding-right: 10px" src="http://pyro.ai/img/pyro_logo.png">

[Pyro](http://pyro.ai/) is a universal probabilistic programming language originally open-sourced by Uber AI Labs. Its applications far exceed what Bayesian Data Analysis covers, but yet is simple enough to apply to bayesian analysis and modelling.

Pyro is built on top of [PyTorch](https://pytorch.org/). More information about Pyro, and the release is available on the [Uber Engineering blog](https://eng.uber.com/pyro/).


## Contents:

2. [Chapter 2: Single Parameter Models.](https://github.com/JamesTrick/bayesian_data_analysis_pyro/blob/master/chapter_2.ipynb)

	This is a great introduction to bayesian models and pyro. In this, we've ported 	examples estimating the sex ratio in births and estimating rates from a poisson 		distribution.
3. [Chapter 3: Multi Parameter Models.](https://github.com/JamesTrick/bayesian_data_analysis_pyro/blob/master/chapter_3.ipynb)
	
    The book now shifts to multi parameter models. It begins by looking at a simple model estimating the speed of light using a Normal model. The code then explores pre-election 	polling and using different priors.

---
Please note, that this is a work in progress. I'll (likely slowly) add chapters over time and update previous ones. Please feel free to raise any issues, contribute fixes and improvements, or even add chapters! :)
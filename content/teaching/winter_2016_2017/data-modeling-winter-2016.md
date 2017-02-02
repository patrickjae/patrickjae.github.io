+++
date = "2016-10-14T17:11:57+02:00"
external_link = "https://moodle.hu-berlin.de/course/view.php?id=73119"
role = ["Lecturer"]
summary = ""
tags = [""]
term = "Winter 2016/2017"
title = "Data Modeling"

+++
## Contents

This seminar will include an introduction to the wide field of Bayesian modeling. We will cover the basics of probabilistic machine learning and then read and discuss different models and techniques for modeling observed data in a Bayesian model. This will naturally include Bayesian mixture models and models of mixed membership. Additional topics include

- latent variable models
- the EM algorithm
- generalized linear models
- hidden Markov models
- statistical inference
  - sampling
  - variational inference

## Recommended literature

Besides the papers that we are covering during the seminar, I recommend the following books. All of these give easy-to-read introductions into the field and can also help you, if you feel you have the need to dive into some topics even more.

1. Hastie, Tibshirani, Friedman: Elements of Statistical Learning, Springer, 2009. The book is [available online](http://www-stat.stanford.edu/~tibs/ElemStatLearn/download.html).
2. Bishop: Pattern Recognition and Machine Learning, Springer, 2006. 
3. Murphy: Machine Learning: A probabilistic perspective. MIT Press, 2012. 

Google will help you in finding an e-copy of each of the books. Alternatively, we have both _Elements of Statistical Learning_ and _Machine Learning: A probabilistic perspective_ in our own library at our offices and I own a copy of _Pattern Recognition and Machine Learning_ that you could borrow.

## Workload
The seminar consists of perpetual attendance and active participation in the discussions. Each of the students will give a talk on one of the topics we are covering. The talk should be between 30-45 minutes, you'll have two weeks time for preparation.
Additionally, each of the students is required to read each paper and prepare a _short_ summary in .5-1 page max. This summary needs to be handed in one day prior to the date at which the paper is presented.
You'll have *two* options for the final report:

1. Write about the paper you presented and put it in a broader scientific context. A rule of thump is, that anyone with a basic technical understanding _but without_ knowledge about the topic should gain an overview, what it is about, why and when to use it as well as when _not_ to use it. A second possibility here is to look deeper into the derivations presented in the paper and to reproduce the steps necessary to arrive at the solutions. This could include e.g. the formal derivation of full conditionals, expectations etc. in the application papers or deriving the natural gradients using the properties of the exponential family in SVI. 

2. Find a dataset that interests you and write about a probabilistic model that can be used to analyze the data in a sense you deem beneficial. Make use of the models and techniques that we cover in the seminar. It is not forbidden to do experiments on the data nor to implement a certain model, although formally this is no requirement (remember, it's a seminar). But doing so will not result in downgrading ;-)

I've created a [template](report_template.zip) to use for your report. Although it is not mandatory, I strongly advise you to use Latex. Use [this cheatsheet](https://wch.github.io/latexsheet/latexsheet-a4.pdf) for basic Latex commands or [this Wikepedia help page](https://en.wikipedia.org/wiki/Help:Displaying_a_formula) for a list of possible symbols, operators, alphabets and typefaces.

[Pew Research](http://www.pewresearch.org/data/download-datasets/), [ICPSR](https://www.icpsr.umich.edu/index.html) and [SAGE](http://methods.sagepub.com/datasets) are good starting points to look for data, although there are plenty more.

The final report should not be longer than **8 pages**.


## List of topics / Syllabus
1. [Introduction to graphical models](papers/graphical_models.pdf)
2. [Latent variable models and mixture models](papers/latent_variable_models.pdf)
1. Bayesian Statistics: model selection, priors, conjugacy (chapter 5 of Murphy: Machine Learning: A probabilistic perspective
3. [The Expectation-Maximization algorithm](papers/EM.pdf)
5. [Statistical inference - sampling](papers/sampling.pdf)
6. [Statistical inference - variational inference](papers/vi.pdf)
8. [Stochastic variational inference](papers/svi.pdf)
9. Hidden Markov models (chapter 13 of Bishop: Pattern Recognition and Machine Learning)
4. [Topic models and applications](papers/topicmodels.pdf)
7. [Probabilistic nonnegative matrix factorization](papers/probabilistic_nmf.pdf)

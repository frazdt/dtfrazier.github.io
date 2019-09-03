---
abstract: A computationally simple approach to inference in state space models is proposed, using approximate Bayesian computation (ABC). ABC avoids evaluation of an intractable likelihood by matching summary statistics for the observed data with statistics computed from data simulated from the true process, based on parameter draws from the prior. Draws that produce a “match” between observed and simulated summaries are retained, and used to estimate the inaccessible posterior. With no reduction to a low-dimensional set ofsufficient statistics being possible in the state space setting, we define the summaries as the maximum of an auxiliary likelihood function, and thereby exploit the asymptotic sufficiency of this estimator for the auxiliary parameter vector. We derive conditions under which this approach—including a computationally efficient version based on the auxiliary score—achieves Bayesian consistency. To reduce the well-documented inaccuracy of ABC in multiparameter settings, we propose the separate treatment of each parameter dimension using an integrated likelihood technique. Three stochastic volatility models for which exact Bayesian inference is either computationally challenging, or infeasible, are used for illustration. We demonstrate that our approach compares favorably against an extensive set of approximate and exact comparators. An empirical illustration completes the article.
authors:
- admin
- Gael M. Martin 
- Brendan P. M. McCabe 
- Worapree Maneesoonthorn
- Christian P. Robert
date: "2019-01-01T00:00:00Z"
doi: ""
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
projects:
- internal-project
publication: '*Journal of Computational and Graphical Statistics*'
publication_short: ""
publication_types:
- "2"
publishDate: "2019-02-27T00:00:00Z"
slides: example
summary: 
tags:
- Source Themes
title: Auxiliary Likelihood-Based Approximate Bayesian Computation in State Space Models
url_code: ""
url_dataset: ""
url_pdf: https://www.tandfonline.com/doi/abs/10.1080/10618600.2018.1552154?journalCode=ucgs20
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
+++
date = "2015-08-22T06:42:21-07:00"
draft = false
title = "Projects"

+++


### Regression-discontinuity designs
In 2014 I was funded by the Institute for Education Sciences (IES) to develop a user-friendly software for educational researchers to perform the analysis of a regression-discontinuity design (RDD). There are already several R packages available that perform these analyses, but we wanted to also provide a graphical user interface, and also add new features. We chose R Shiny to program our graphical interface, and we have added some functionality that is not covered by existing R packages. Among them are the analysis of RDDs with two assignment variables (and all the resulting complications with regards to effect estimation and sensitivity checks), and the estimation of statistical power for any type of RDD using Monte Carlo methods. 


### Missing data
Missing data is almost everywhere, and I became interested in this topic by working with Craig Enders, the author of a popular missing data textbook. I was especially interested in expressing assumptions about the missingness using graphical models, and have worked with Karthika Mohan on this topic. Some of the missingness assumptions can also be encoded in graphs, and this is often helpful in thinking about the underlying causal mechanism that resulted in some datapoints being missing. It also yields insights into the fact that there are auxiliary variables that can increase bias, a topic that I researched together with Norman Rose. 


### Propensity scores
My interest in propensity score methods started during my Ph.D. program. I conducted a systematic review of the use of propensity scores in psychology. In the review me and my co-author focused on how psychological researchers use propensity scores, and how they report it. Overall, researchers in psychology do a decent job when using propensity scores, but the reporting was lacking. We provided some guidelines of what we considered minimally acceptable reporting standards. My dissertation topic was on the use of propensity scores for multi-level data (meaning data in which some form of clustering occurs). Through some analytic work, and a large simulation study, I tried to determine what kind of model specification, and matching scheme might be most appropriate in such settings. It seems that random-effects models for the estimation of the propensity score, and then matching within clusters seems to work well. Later this work was extended by my colleague Peter Steiner. He was awarded a grant by the Institute for Education Sciences (IES) to investigate these issues further. 
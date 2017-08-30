DataTalks
#########


This is the home for the `DataTalks <https://www.meetup.com/DataHack>`_ meetup series and other events by `DataHack <http://datahack-il.com/>`_, like our annual hackathon. :) 

The `DataTalks <https://www.meetup.com/DataHack>`_ meetup series is hosted by different companies, with each meetup usually featuring two speakers. Talks touch on a variety of subjects in machine learning, statistics, data engineering and other data science related topics. 

You can also find us on `Facebook <https://www.facebook.com/datahackil/>`_, `Twitter <https://twitter.com/DataHackIL/>`_ and join `our monthly newsletter <join our monthly newsletter>`_. 

|

.. contents:: **Past meetups:**

.. section-numbering:

|

DataTalks #1: Web traffic estimation and big ML workflows 
=========================================================

Roy Yadoo, SimilarWeb - Web traffic estimation as a meta-analysis challenge
------------------------------------------------------------------------------------
**Speaker:** Roy Yadoo, SimilarWeb

**Title:** Web traffic estimation as a meta-analysis challenge

**Abstract:** Every day, users around the world make over 10 billion visits to websites on their personal computers and mobile devices. Understanding the underlying patterns and behaviors is a central challenge in web research. At SimilarWeb, our goal is to measure and analyze the traffic of each website and mobile app in the digital world, with over 60 million sites and apps estimated daily. Our estimations rely on a variety of data sources, including our panel with millions of web users. Data sources in our panel can vary by size, bias and engagement. The challenge is to find a common truth among the noise, while considering additional business requirements, such as the competing objectives of accuracy vs. consistency. 
In this talks, I will present several approaches used at SimilarWeb for estimation, such as robust regressions, Bayesian estimators, outlier detection and others. 



Daniel Marcous, Google - Production-Ready BIG ML Workflows: From zero to hero
------------------------------------------------------------------------------------
**Speaker:** Daniel Marcous, Google

**Title:** Production-Ready BIG ML Workflows: From zero to hero

**Abstract:** Data science isn't an easy task to pull of. You start with exploring data and experimenting with models. Finally, you find some amazing insight!

What now? How do you transform a little experiment to a production ready workflow? Better yet, how do you scale it from a small sample in R/Python to TBs of production data? 
Building a BIG ML Workflow - from zero to hero, is about the work process you need to take in order to have a production ready workflow up and running.

Covering:

* Small - Medium experimentation (R) 
* Big data implementation (Spark Mllib /+ pipeline) 
* Setting Metrics and checks in place 
* Ad hoc querying and exploring your results (Zeppelin) 
* Painpoints & Lessons learned the hard way (is there any other way?)

**Slides:** http://www.slideshare.net/DanielMarcous/productionready-big-ml-workflows-from-zero-to-hero

**Code:** https://github.com/dmarcous/BigMLFlow



DataTalks #2: Markov blankets for feature selection & app mentions in texts 
===========================================================================

Avishay Meron, PayPal - On feature selection: Key ideas and utilization in fraud analysis
-----------------------------------------------------------------------------------------
**Speaker:** Avishay Meron, PayPal

**Title:** On feature selection: Key ideas and utilization in fraud analysis

**Abstract:** Feature selection has been a fertile field of research since the 70’s and proven to increase efficiency and accuracy in learning tasks. In the past decade data has become increasingly larger in both number of instances and number of features. This enormity poses sever challenges with respect to scalability and learning performance. Since the task of feature selection is NP-hard, we are left to approximate a good solution using various heuristics. In this talk we review key ideas and try to sketch guide lines on which heuristic should we follow given a learning task. In addition, we present a utilization of Markov Blankets feature selections for fraud analysis. 



Doron Kukliansky, Facebook - App mentions in texts
--------------------------------------------------
**Speaker:** Doron Kukliansky, Facebook

**Title:** App mentions in texts

**Abstract:** As people move further away from desktop usage and spend more of time on their mobile devices, mobile apps are changing the way we interact with the Internet. But how can we identify which apps are really trending and why? This technical talk will discuss the implementation details of a small identification engine that identifies when mobile apps are mentioned in Facebook posts and are covered in the media. We will start from a simple idea and develop it, step by step, to reach our final algorithm. We will use only basic concepts from probability, statistics, machine learning and NLP, but dive deeper into their meaning and applications, to gain additional insights into the problem.

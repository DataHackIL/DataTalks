DataTalks
#########


This is a list of past talks in the  `DataTalks <https://www.meetup.com/DataHack>`_ meetup series by `DataHack <http://datahack-il.com/>`_.

The `DataTalks <https://www.meetup.com/DataHack>`_ meetup series is hosted by different companies, with each meetup usually featuring two speakers, where at least one of the speakers - and sometimes both - is not an employee of the hosting company. Talks touch on a variety of subjects in machine learning, statistics, data engineering and other data science related topics. 

You can also find us on `Facebook <https://www.facebook.com/datahackil/>`_, `Twitter <https://twitter.com/DataHackIL/>`_ and join `our monthly newsletter <join our monthly newsletter>`_. 

|

.. contents:: **Past meetups:**

.. section-numbering:

|

DataTalks #1: Web traffic estimation and big ML workflows 
=========================================================
**Event page:** https://www.meetup.com/DataHack/events/231012715/

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
**Event page:** https://www.meetup.com/DataHack/events/232842934/

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




DataTalks #3: Dive into Data Science with Python 
================================================
**Event page:** https://www.meetup.com/DataHack/events/237926275/

Yoav Ram, Stanford - Dive into Scientific Python
------------------------------------------------
**Speaker:** Yoav Ram, Stanford

**Title:** Dive into Scientific Python

**Abstract:** I will introduce the Python programming language and demonstrate how Scientific Python can be used to study evolutionary theory using mathematical and computational models. We'll see how to run fast evolutionary simulations with NumPy and Cython, analyze and visualize simulation results with Pandas and Seaborn, and find solutions to evolutionary models using SciPy. This talk is a wonderful opportunity to learn about Scientific Python through actual research-based examples, as well as an occasion to to discover how theoretical evolutionary biologists approach their research.

**Recording:** https://www.youtube.com/watch?v=2MnSfWD44IM

**Slides:** https://github.com/yoavram/DataTalks2017

**Code:** https://github.com/yoavram/PyConIL2016  (take a look at ``notebook.ipynb``)



Shay Palachy, Neura - Quick & dirty data science in Python
----------------------------------------------------------
**Speaker:** Shay Palachy, Neura  

**Title:** Quick & dirty data science in Python

**Abstract:** In this talk I will present a classification challenge we had at Neura, and how we tackled it, using the simplest machine learning tools and some dirty heuristics to get a working system with good results in a short amount of time. 



DataTalks #4: Python on Spark and location-based search
=======================================================
**Event page:** https://www.meetup.com/DataHack/events/239689575/

Erez Barshir, Easy - Data Science in location-based search
------------------------------------------------
**Speaker:** Erez Barshir, Easy

**Title:** Data Science in location-based search

**Abstract:** Local businesses are changing fast. In Israel alone, every two or three minutes some local business changes substantially (open/close/changes location). This means that keeping a dataset of local businesses up-to-date manually is a costly and non-scalable operation. One important aspect of this problem is trying to determine whether a local business is permanently closed. We will examine a data science-based approach to this problem and try to answer some related and more nuanced questions. We will see some of Easy's engineering, real data and code and general approach to such issues. 


Alex Landa, Trainologic - Python Spark Intro for Data Scientists
----------------------------------------------------------------
**Speaker:** Alex Landa, Trainologic

**Title:** Python Spark Intro for Data Scientists 

**Abstract:** As a data scientist you need to know how to handle large data sets, how to clean them, analyze them and get conclusions from them. Spark is a mandatory tool for that - a distributed computation engine that enables you to run map-reduce tasks using a friendly Python (and Scala) API. After this talk you will understand what Spark is and how to start using it. We will cover Spark architecture and workflow, understand the usage of RDD and DataFrame APIs and see some hands-on examples.

**Slides and code:** http://trainologic.com/python-spark-intro-data-scientists-2/



DataTalks #4.5: A Shallow Introduction to Deep Learning
=====================================================
**Event page:** https://www.meetup.com/DataHack/events/239977617/

Dr. Eyal Gruss - A Shallow Introduction to Deep Learning
------------------------------------------------
**Speaker:** Dr. Eyal Gruss

**Title:** A Shallow Introduction to Deep Learning

**Abstract:** We've partnered with Dr. Eyal Gruss for an introductory lecture to deep learning, in which he will cover the latest innovations in Computer Vistion, NLP and other fields. *Note: Unlike most of our meetups, this is an introductory lecture. It DOES NOT require previous knowledge. It is not recommended for people with background in deep learning, but highly recommended for people looking to get into the field or get an idea of what it's about.*

**Slides:** http://bit.ly/introduction-deep-learning




DataTalks #5: Advanced Topics in Clustering
===========================================

**Event page:** https://www.meetup.com/DataHack/events/242507384/

Ilai Falach, StoreSmarts - K-means++: Harder, Better, Faster, Stronger
----------------------------------------------------------------------
**Speaker:** Ilai Falach, StoreSmarts

**Title:** K-means++: Harder, Better, Faster, Stronger

**Abstract:** In this talk I will give an overview of center-based clustering methods, starting from the well known k-center and k-means methods. These will give the motivation for the k-means++ method, which extends k-means by making the random initialization of data points more intelligent. We will show guarantees on convergence and approximation of the algorithm, and go through the actual proofs.

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_5/clustering-intro-center-based.pdf


Nadav Bar, Google - A Practical Intro To Density Based Clustering
-----------------------------------------------------------------
**Speaker:** Nadav Bar, Google

**Title:** A Practical Intro To Density Based Clustering

**Abstract:** Although they have received less attention compared to Centroid-based clustering methods, such as k-means, density based clustering methods offer some very appealing features for their users, including the ability to discover the number of clusters automatically, as well as the detection of clusters of different shapes and sizes. In this talk, I will present several density-based clustering methods, starting from the classic DBSCAN method, and moving forward to newer and more advanced methods. As part of the talk, we will walk through each algorithm’s inner workings, and we will also see live code examples for each of the clustering methods.

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_5/density_clustering_datahack_meetup.pdf
**Code:** https://github.com/nadavbar/density-based-clustering

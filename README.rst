DataTalks
#########


This is a list of past talks in the  `DataTalks <https://www.meetup.com/DataHack>`_ meetup series by `DataHack <http://datahack-il.com/>`_.

DataTalks homepage: https://www.meetup.com/DataHack/

The `DataTalks <https://www.meetup.com/DataHack>`_ meetup series is hosted by different companies, with each meetup usually featuring two speakers, where at least one of the speakers - and sometimes both - is not an employee of the hosting company. Talks touch on a variety of subjects in machine learning, statistics, data engineering and other data science related topics. 

You can also find us on `Facebook <https://www.facebook.com/datahackil/>`_, `Twitter <https://twitter.com/DataHackIL/>`_ and join `our monthly newsletter <https://mailchi.mp/2c67d69eb667/datahack-newsletter>`_. 

|

.. contents:: **Past meetups:**

.. section-numbering:

|

DataTalks #1: Web traffic estimation and big ML workflows 
=========================================================
**Event page:** https://www.meetup.com/DataHack/events/231012715/

Roy Yadoo, SimilarWeb - Web traffic estimation as a meta-analysis challenge :vertical_traffic_light:
------------------------------------------------------------------------------------
**Speaker:** Roy Yadoo, SimilarWeb

**Title:** Web traffic estimation as a meta-analysis challenge

**Abstract:** Every day, users around the world make over 10 billion visits to websites on their personal computers and mobile devices. Understanding the underlying patterns and behaviors is a central challenge in web research. At SimilarWeb, our goal is to measure and analyze the traffic of each website and mobile app in the digital world, with over 60 million sites and apps estimated daily. Our estimations rely on a variety of data sources, including our panel with millions of web users. Data sources in our panel can vary by size, bias and engagement. The challenge is to find a common truth among the noise, while considering additional business requirements, such as the competing objectives of accuracy vs. consistency. 
In this talks, I will present several approaches used at SimilarWeb for estimation, such as robust regressions, Bayesian estimators, outlier detection and others. 



Daniel Marcous, Google - Production-Ready BIG ML Workflows: From zero to hero :trophy:
--------------------------------------------------------------------------------
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

Avishay Meron, PayPal - On feature selection: Key ideas and utilization in fraud analysis :dollar:
-----------------------------------------------------------------------------------------
**Speaker:** Avishay Meron, PayPal

**Title:** On feature selection: Key ideas and utilization in fraud analysis

**Abstract:** Feature selection has been a fertile field of research since the 70’s and proven to increase efficiency and accuracy in learning tasks. In the past decade data has become increasingly larger in both number of instances and number of features. This enormity poses sever challenges with respect to scalability and learning performance. Since the task of feature selection is NP-hard, we are left to approximate a good solution using various heuristics. In this talk we review key ideas and try to sketch guide lines on which heuristic should we follow given a learning task. In addition, we present a utilization of Markov Blankets feature selections for fraud analysis. 



Doron Kukliansky, Facebook - App mentions in texts :iphone:
--------------------------------------------------
**Speaker:** Doron Kukliansky, Facebook

**Title:** App mentions in texts

**Abstract:** As people move further away from desktop usage and spend more of time on their mobile devices, mobile apps are changing the way we interact with the Internet. But how can we identify which apps are really trending and why? This technical talk will discuss the implementation details of a small identification engine that identifies when mobile apps are mentioned in Facebook posts and are covered in the media. We will start from a simple idea and develop it, step by step, to reach our final algorithm. We will use only basic concepts from probability, statistics, machine learning and NLP, but dive deeper into their meaning and applications, to gain additional insights into the problem.




DataTalks #3: Dive into Data Science with Python 
================================================
**Event page:** https://www.meetup.com/DataHack/events/237926275/

Yoav Ram, Stanford - Dive into Scientific Python :microscope::snake:
------------------------------------------------
**Speaker:** Yoav Ram, Stanford

**Title:** Dive into Scientific Python

**Abstract:** I will introduce the Python programming language and demonstrate how Scientific Python can be used to study evolutionary theory using mathematical and computational models. We'll see how to run fast evolutionary simulations with NumPy and Cython, analyze and visualize simulation results with Pandas and Seaborn, and find solutions to evolutionary models using SciPy. This talk is a wonderful opportunity to learn about Scientific Python through actual research-based examples, as well as an occasion to to discover how theoretical evolutionary biologists approach their research.

**Recording:** https://www.youtube.com/watch?v=2MnSfWD44IM

**Slides:** https://github.com/yoavram/DataTalks2017

**Code:** https://github.com/yoavram/PyConIL2016  (take a look at ``notebook.ipynb``)



Shay Palachy, Neura - Quick & dirty data science in Python :poop::snake:
----------------------------------------------------------
**Speaker:** Shay Palachy, Neura  

**Title:** Quick & dirty data science in Python

**Abstract:** In this talk I will present a classification challenge we had at Neura, and how we tackled it, using the simplest machine learning tools and some dirty heuristics to get a working system with good results in a short amount of time. 



DataTalks #4: Python on Spark and location-based search
=======================================================
**Event page:** https://www.meetup.com/DataHack/events/239689575/

Erez Barshir, Easy - Data Science in location-based search :globe_with_meridians:
------------------------------------------------
**Speaker:** Erez Barshir, Easy

**Title:** Data Science in location-based search

**Abstract:** Local businesses are changing fast. In Israel alone, every two or three minutes some local business changes substantially (open/close/changes location). This means that keeping a dataset of local businesses up-to-date manually is a costly and non-scalable operation. One important aspect of this problem is trying to determine whether a local business is permanently closed. We will examine a data science-based approach to this problem and try to answer some related and more nuanced questions. We will see some of Easy's engineering, real data and code and general approach to such issues. 


Alex Landa, Trainologic - Python Spark Intro for Data Scientists :snake::boom:
----------------------------------------------------------------
**Speaker:** Alex Landa, Trainologic

**Title:** Python Spark Intro for Data Scientists 

**Abstract:** As a data scientist you need to know how to handle large data sets, how to clean them, analyze them and get conclusions from them. Spark is a mandatory tool for that - a distributed computation engine that enables you to run map-reduce tasks using a friendly Python (and Scala) API. After this talk you will understand what Spark is and how to start using it. We will cover Spark architecture and workflow, understand the usage of RDD and DataFrame APIs and see some hands-on examples.

**Slides and code:** http://trainologic.com/python-spark-intro-data-scientists-2/



DataTalks #4.5: A Shallow Introduction to Deep Learning 
=====================================================
**Event page:** https://www.meetup.com/DataHack/events/239977617/

Dr. Eyal Gruss - A Shallow Introduction to Deep Learning :fish::orange_book:
------------------------------------------------
**Speaker:** Dr. Eyal Gruss

**Title:** A Shallow Introduction to Deep Learning

**Abstract:** We've partnered with Dr. Eyal Gruss for an introductory lecture to deep learning, in which he will cover the latest innovations in Computer Vistion, NLP and other fields. *Note: Unlike most of our meetups, this is an introductory lecture. It DOES NOT require previous knowledge. It is not recommended for people with background in deep learning, but highly recommended for people looking to get into the field or get an idea of what it's about.*

**Slides:** http://bit.ly/introduction-deep-learning




DataTalks #5: Advanced Topics in Clustering
===========================================

**Event page:** https://www.meetup.com/DataHack/events/242507384/


Ilai Fallach, StoreSmarts - K-means++: Harder, Better, Faster, Stronger :sparkles:
----------------------------------------------------------------------
**Speaker:** Ilai Fallach, StoreSmarts

**Title:** K-means++: Harder, Better, Faster, Stronger

**Abstract:** In this talk I will give an overview of center-based clustering methods, starting from the well known k-center and k-means methods. These will give the motivation for the k-means++ method, which extends k-means by making the random initialization of data points more intelligent. We will show guarantees on convergence and approximation of the algorithm, and go through the actual proofs.

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_5/clustering-intro-center-based.pdf


Nadav Bar, Google - A Practical Intro To Density Based Clustering :new_moon:
-----------------------------------------------------------------
**Speaker:** Nadav Bar, Google

**Title:** A Practical Intro To Density Based Clustering

**Abstract:** Although they have received less attention compared to Centroid-based clustering methods, such as k-means, density based clustering methods offer some very appealing features for their users, including the ability to discover the number of clusters automatically, as well as the detection of clusters of different shapes and sizes. In this talk, I will present several density-based clustering methods, starting from the classic DBSCAN method, and moving forward to newer and more advanced methods. As part of the talk, we will walk through each algorithm’s inner workings, and we will also see live code examples for each of the clustering methods.

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_5/density_clustering_datahack_meetup.pdf
**Code:** https://github.com/nadavbar/density-based-clustering



DataTalks #6: DataHack Champions
================================

Our sixth meetup was hosted by Taboola, and featured cool past projects done in DataHack.  

**Event page:** https://www.meetup.com/DataHack/events/242508298/

Sria  Louis, The Hebrew University -  Using graph-based features to predict ship type :ship:
----------------------------------------------------------------------
**Speaker:** Sraia  Louis, The Hebrew University of Jerusalem

**Title:** Using graphs to predict ship type according to ship behavior

**Abstract:** Given the behavior of ships such as port visits and ship-to-ship meetings - we are trying to categorize ship type based on ship behavior: oil, container, fishing etc. In this talk we will discuss how engineering new features based on the graph that a ship spans can capture a ship's behavior and thus improve classification accuracy. We will present the problem, the mathematical tools and some intuition - and for the fun we will conclude with failure points (and possible solutions).

**Video:** https://www.youtube.com/watch?v=xk3Z0zgbS4I

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_6/DataTalks_6_Sea_snails.pdf


Seffi Cohen, IDF -  Ensemble models approach for cab ride duration prediction :taxi:
----------------------------------------------------------------------
**Speaker:** Seffi Cohen, Chief Data Scientist, IDF

**Title:** A model ensemble approach for cab ride duration prediction

**Abstract:** In this talk I'll share how we attempted to predict a cab ride duration using various generated features and models, and how we settled on a model ensemble approach to utilize the advantages of different models and used it to win the Final challenge of DataHack 2016. I will also talk about ensemble methods, how to choose a model that will give good results in a short amount of time and how to engineer and choose good features. Finally, I will share lessons learned from multiple kaggle competitions and being part of winning teams in DataHack for two years in a row.

**Video:** https://www.youtube.com/watch?v=8d_9n10s3SQ

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_6/datatalks_6-eta_prediction_challenge.pdf


Doron Kukliansky -  Data Driven Video Creation :video_camera:
-------------------------------------------------------
**Speaker:** Doron Kukliansky

**Title:** Data Driven Video Creation

**Abstract:**  In this talk we will discuss our DataHack project in which we attempted to generate new episodes of The Simpsons, using data science tool. We will see the general approach, the data we had, but more importantly, the data we did not have and how we compensated for it. We will also deep dive into two technical problems we encountered during the project and are of general interest:

- The first is speaker recognition, for which we'll discuss the MFCC features and how they can be used for classification.

- The second is semantic sentence similarity, for which we'll discuss the Word Mover's Distance, it's origin and usage.

*(prior familiarity with The Simpsons isn't necessary but is an advantage)*

**Video:** https://www.youtube.com/watch?v=GwKq3pHkNc0

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_6/DataTalks_6-SimPhony.pdf




DataTalks #7:  Topics in Online Learning
========================================

Our seventh meetup was hosted by Booking.com, and was focused on online learning.

**Event page:** https://www.meetup.com/DataHack/events/248628019/


Michal Moshkovitz, The Hebrew University of Jerusalem - What Cannot Be Learned With Bounded Memory? 💾
------------------------------------------------------------------------------------------------------
**Speaker:** Michal Moshkovitz, The Hebrew University of Jerusalem

**Title:** What Cannot Be Learned With Bounded Memory?

**Abstract:** How does computational online learning change when one cannot store all the examples one sees in memory? This question has seen a burst of interest in the past couple of years, leading to the surprising theorem that there exist simple concepts (parities) that require an extraordinary amount of time to learn unless one has quite a lot of memory. In this work we show that in fact most concepts cannot be learned without sufficient memory. This subsumes the aforementioned theorem and implies similar results for other concepts of interest. The new results follow from a general combinatorial framework that we developed to prove lower bounds for space bounded learning.

**About the speaker:** Michal Moshkovitz is a Ph.D. student at The Edmond & Lily Safra Center for Brain Sciences at The Hebrew University of Jerusalem, Israel. She is researching machine learning inspired by neuroscience and aided by tools from theoretical computer science and combinatorics.

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_7/DataTalks7-Michal_Moshkovitz-What_Cannot_Be_Learned_With_Bounded_Memory.pdf


Kristian Holsheimer, Booking.com - FTRL Formulations For Online Learning 📱📚
-----------------------------------------------------------------------------
**Speaker:** Kristian Holsheimer, Booking.com

**Title:** FTRL Formulations For Online Learning

**Abstract:** What do you do when you want to train a machine learning model on a dataset that doesn't fit in memory? There's been a lot of attention on scalable machine learning solutions that look very promising, but require access to a large data cluster. In this talk I'll present a scalable machine learning solution that works on your own laptop. In particular, I'll explain how to use online learning as a scalable technique for (batch) machine learning, with some specific business applications from Booking.com. I'll also provide some reasoning and intuition as to why this online learning approach works so well in settings for which it wasn't originally intended. Along the way, we'll touch upon an interesting formulation of online learning known as "Follow The Regularized Leader" (FTRL).

**About the speaker:** Kris is a data scientist at Booking.com with experience in applied machine learning for advertising and fraud prevention. Kris' background is in theoretical physics, with a PhD in string theory from the University of Amsterdam.

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_7/DataTalks7-Kristian_Holsheimer-Online_and_out-of-core_learning_with_FTRL.pdf


DataTalks #8: Topics in statistics - Bayesian inference and independence tests
==============================================================================

Our eigth meetup was hosted by Taboola, and was focused on topics in statistics.

**Event page:** https://www.meetup.com/DataHack/events/256061145/


Eric Novik, Generable - High Dimensional Bayesian Inference with Stan 🔬
-----------------------------------------------------------------------
**Speaker:** Eric Novik, Generable

**Title:** High Dimensional Bayesian Inference with Stan

**Abstract:** Big data is everywhere but it takes more than running one million logistic
regressions in parallel to make sense of it. As the size of datasets increase, we can start modeling the underlying phenomena with higher and higher precision.
As the model complexity expands, our task of fully characterizing the uncertainty of all the unknowns becomes exponentially difficult. This problem eluded statistical computing until recently when we learned how to efficiently sample from high-dimensional distributions.
In this talk, I will describe the problem posed by Bayesian learning, how it compares to traditional ML (ML: Machine Learning or Maximum Likelihood), and show how we use these methods to solve difficult problems clinical research.

**About the speaker:** Eric Novik is an applied statistician and CEO of Generable. At Generable, Eric is responsible for the strategic direction, probabilistic modeling, and scope and requirements of the company's clinical research platform. Prior to Generable, Eric was a senior data scientist at TIBCO Spotfire where he built statistical applications for customers in Pharma and Finance sectors. In 2010, Eric started Risktail, an analytics software company. He has an MA in Statistics from Columbia University.


**Slides:** TBA


Or Zuk, HUJI - Testing Independence with Biased Sampling 💪👨👨👨 
---------------------------------------------------------------
**Speaker:** Or Zuk, The Hebrew University of Jerusalem

**Title:** Testing Independence with Biased Sampling

**Abstract:** Testing for association, or dependency, between pairs of random variables is a fundamental problem in statistics, and such tests are performed for many pairs of variables in large scale modern datasets. In some applications, one needs to test independence of two random variables X and Y, given observations with known biased sampling.
The biased sampling is formulated using a non-negative weighing function w(x,y), such that we observe samples from a density proportional to f_XY(x,y) * w(x,y), and if not dealt with properly, may confound our tests for dependency in the (unbiased) density f_XY. This problem generalizes a well known truncation model obtained by taking w(x,y)=I(x(i) an asymptotic bootstrap-based approach and (ii) an exact permutation-test with non-uniform sampling of permutations using MCMC. We show that our test is consistent for important special cases of the problem, and achieves improved power compared to competing methods.

**About the speaker:** Or Zuk is a faculty member at the department of statistics at the Hebrew University. He was a visited professor at the Toyota technical institute in Chicago, did a post doc at Broad institute and received his Ph.D. in Computer Science and Applied Mathematics from the Weizmann Institute. His research focuses on statistical and algorithmic problems arising from genomics applications.

**Slides:** TBA


DataTalks #9:  Mastering Catboost and XGBoost in Production
===========================================================

Our ninth meetup was hosted by PerimeterX, and was focused on gradient boosted trees.

**Event page:** https://www.meetup.com/DataHack/events/257155216/


Tal Peretz - Mastering The New Generation of Gradient Boosting 🐱🌳
------------------------------------------------------------------
**Speaker:** Tal Peretz

**Title:** Mastering The New Generation of Gradient Boosting

**Abstract:** Gradient Boosted Decision Trees are the hottest ML models for tabular data. These models have already taken over Kaggle and are now taking over the industry. In this talk, we are going to explore and compare XGBoost, LightGBM & the cool kid on the block - Catboost.

**About the speaker:** Tal Peretz is a Data Scientist, Software Engineer, and a Continuous Learner. You may know him as DataHack 2018 1st prize winner (with his brother). Previously, he founded and lead the Israeli Air Force Data Science team. Nowadays he is leveraging ML to fight fraud at simplex.com. Tal also writes for KDnuggets, Towards Data Science and HackerNoon. You can reach him at talperetz.com

**Video:** https://www.youtube.com/watch?v=V6nMkUiBdTI&t=0s&index=7&list=PLZYkt7161wELBhCKNMMthhNo61Z2k8xtu

**Slides:** TBA

**More details:** https://talperetz.github.io/Tal-Peretz/mastering_the_new_generation_of_gradient_boosting/mastering_the_new_generation_of_gradient_boosting.html


Barak Amar, PerimeterX - Boosting Trees in Production 🚀🌳 
-------------------------------------------------------------
**Speaker:** Barak Amar, PerimeterX

**Title:** Boosting Trees in Production

**Abstract:** Boosted trees is one of the most useful and common techniques for predictive modeling, and it is used by many of our models.

When developing a new model, we go through many iterations of research and production and thus we had to find a way to effectively propagate changes from the research to the production pipeline. Generally, we can classify these changes into one of two types: feature-engineering changes (i.e. features pre-processing logic) and model topology changes (e.g. tree depth, number of trees, etc.). Our goal was to achieve a simple architecture that would allow us to propagate these changes without the need to write additional production side code.

This presentation will introduce the main solutions and approaches that are in use by the community today, together with their advantages and disadvantages. We will also present the actual solution implemented in our production flow together with some important best-practices learnt the hard way.

**About the speaker:** Barak Amar is a software architect at PerimeterX.

**Video:** https://www.youtube.com/watch?v=AVhcVraKXis&index=7&list=PLZYkt7161wELBhCKNMMthhNo61Z2k8xtu

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_9/Boosting%20Trees%20in%20Production%20-%20DataTalks%20%239%20Meetup%202019-01-22.pdf



DataTalks #10: Topics in Adversarial Learning
=============================================

Our tenth meetup was hosted by Oracle Data Cloud, and was focused on adversarial learning.

**Event page:** https://www.meetup.com/DataHack/events/258554649/


Gal Yona - An Introduction to Adversarial Examples 🔫📌
--------------------------------------------------------
**Speaker:** Gal Yona

**Title:** An Introduction to Adversarial Examples

**Abstract:** It has recently been established that neural networks are extremely vulnerable to adversarial attacks. These are adversarially chosen inputs, which - despite being almost indistinguishable from natural data (to a human observer) - can easily fool the network into wrong (even silly) predictions. What could explain the vulnerability of DL to such attacks? And most importantly, can networks be trained to withstand them?

In this talk, I will give a general, high-level introduction to this exciting field of research. We will emphasize the fact that the current solutions are in fact a particular instantiation of Adversarial Learning, a general formulation that can be incredibly useful even without the threat of real-life adversaries.

**About the speaker:** Gal Yona is a Ph.D. student at the Weizmann Institute of Science. Her research is focused on the concerns and implications involved with deploying algorithmic (particularly, machine learning) tools in high-stakes environments. In particular, she works on addressing issues of fairness and non-discrimination, interpretability and robustness from a computational perspective.

**Video:** https://www.youtube.com/watch?v=Z9D87D_zkOA&list=PLZYkt7161wELBhCKNMMthhNo61Z2k8xtu&index=11&t=10s

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_10/DataTalks%2010%20-%20Gal%20Yona%20-%20A%20Brief%20Introduction%20to%20Adversarial%20Examples.pdf


Yossi Adi - Beyond Classification: Extending and Leveraging Adversarial Examples 🤸🏽‍♀️🏋 
--------------------------------------------------------------------------------------
**Speaker:** Yossi Adi

**Title:** Beyond Classification: Extending and Leveraging Adversarial Examples

**Abstract:** In this talk, I'll focus on three main topics: (i) generating adversarial examples for structured tasks; (ii) defenses against adversarial examples and the detection of such; (iii) the use of adversarial examples for our own good.
First, I'll describe Houdini, a novel flexible approach for generating adversarial examples specifically tailored for the final measure of performance of the task, considered be it combinatorial and non-decomposable. I'll demonstrate how Houdini can be applied to a range of applications such as speech recognition, speaker verification, pose estimation and semantic segmentation. Next, in the context of defenses against adversarial examples, I'll present several approaches for defending against adversarial examples and detecting adversarial attacks by investigating the network's behavior only. Lastly, I'll suggest few ideas on how can one use this weakness of neural networks for his own benefit.

**About the speaker:** Yossi Adi is a Ph.D. candidate at Bar-Ilan University, in the Machine Learning for Speech and Language Processing Laboratory under the supervision of Prof. Joseph Keshet. He received an M.Sc. degree from Bar-Ilan University in 2015. His research spans both core machine learning methods and their security aspects, concentrating on speech recognition, speech and audio processing, and sequential tasks. Mr. Adi is also the drummer and founder of Lucille Crew - an international groove collective, fusing elements of Hip-Hop, Funk & Soul.

**Video:** https://youtu.be/42Zt58IqjuY

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_10/DataTalks%2010%20-%20Yossi%20Adi%20-%20Beyond%20Classification-%20Extending%20and%20%20Leveraging%20Adversarial%20Examples.pdf



DataTalks #11: App Store Optimization and Life-Time Value Prediction
====================================================================

Our eleventh meetup was hosted by Playstudios Israel and StoreMaven, and explored how two companies are using data science to perform App Store optimization and Life-Time Value prediction.

**Event page:** https://www.meetup.com/DataHack/events/262090862/


Michael Kozak - Boosting UA Performances with User LTV Predictive Models 💉📱
-----------------------------------------------------------------------------
**Speaker:** Michael Kozak

**Title:** Boosting UA Performances with User LTV Predictive Models

**Abstract:** Predicting users' Life-Time Value (LTV) is a highly required demand across the marketing domain. An accurate model yields better optimization by smartly allocating budget between ad network, shortening the recoup period and reducing risk in investment. A challenge in this context is that marketing managers need to know where the winds blow very early in the business unit's lifetime to make decisions. Gaming companies encounter yet another challenge as social games traditionally have low paying rate, which makes the data-set imbalanced.
How can we predict our users' behavior, based solely on their first few days in the app?

In this talk, I will go through the benefits on building your LTV model on the user level, what components this LTV model has, how to test your model performance, and finally, how you can exploit the LTV model into other domains in your business.

**About the speaker:** Michael Kozak holds a Bachelor's degree in Industrial Engineering and a Master's degree in Statistics. He focuses his entire work in the Playstudios' UA team, creating predictive models to assist the day-to-day UA activity.

**Video:** TBA

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_11/Michael%20Kozak%2C%20Playstudios%20-%20Boosting%20UA%20Performance%20with%20User%20LTV%20Predictive%20Models.pdf


Roy Berkowitz - Multi-Armed Bandit for App Store Optimization 🖐🖖👋🔫💰🛍
---------------------------------------------------------------------------
**Speaker:** Roy Berkowitz

**Title:** Multi-Armed Bandit for App Store Optimization

**Abstract:** The transition from web to mobile has mobile app developers faced with numerous challenges in creating sustainable growth. While on the web all traffic goes through the website, where tools such as Google Analytics for intelligence and A/B testing through Optimize, provide many insights, these simply don’t exist for mobile.

With the App Store acting as a gateway, where 100% of users have to pass through to download an app, your App Store presence is becoming essentially your new “homepage”, hugely impacting your business success. Understanding a user’s behavior is what will enable marketers and UA teams to crack the marketing challenge that comes with the App Store environment. The key to unlocking this challenge lies in implementing a solution that creates usable data insights that can then be implemented.

That is the challenge that StoreMaven tackled. By inventing a solution that enables the market to analyze and test their app store, StoreMaven is transforming the way top app developers like Facebook, Zynga, Uber, and Warner Brothers optimize their app’s marketing performance and answering the question: How do we test our app store to gain insights that lead us to concrete, easily implemented results.
In this talk, I am going to present how StoreMaven’s proprietary algorithm StoreIQ works to find the best variation in multi variable testing on the App Store. The algorithm, based on “Multi-Armed-Bandit” concepts, continuously evolves using billions of App Store engagement observations to ensure accuracy.

**About the speaker:** As the Director of Data at StoreMaven, Roy focuses on leveraging data to enable informed decision making and is passionate about hacking data problems to optimize the mobile growth world.

**Video:** TBA

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_11/StoreIQ%20-%20The%20Multi-Armed%20Bandit%20for%20App%20Store%20Optimization%20by%20StoreMaven.pdf



DataTalks #12: Test Driven Data Science and The Power of Weak Supervision
=========================================================================

Our 12th meetup was hosted by Check Point and explored how spending more time with your data can drive the creation of better models -- even with no supervised signal at all!

**Event page:** https://www.meetup.com/DataHack/events/263386803/


Gershon Celniker - "Know Your Data!" Test Driven Data Science
-----------------------------------------------------------------------------
**Speaker:** Gershon Celniker

**Title:** "Know Your Data!" Test Driven Data Science

**Abstract:** Knowing Your Data is a crucial factor for Machine learning. We all familiar with the term Garbage in, Garbage out (or GIGO for short) originated in the statistics and data science fields to illustrate the fact that
the quality of the output received from a ML model depends greatly on the quality of the information that was input. If your data is not valid or accurate, your results are worthless. “Garbage data” can be data that is
simply filled with errors, outliers, missing values and artifacts but it can also be data that doesn't have any applicability.

The solution is to take out your data trash! by spending less time on “fit/predict” but spending more time on crunching and validating the input data to ensure that the right sort of data goes into the model. In this talk I will tackle this problem of data integrity for Machine learning purposes. I will go over some highly recommended data-driven methodologies and best practices to ensure the quality of the training data for ML modeling. I will present several use-cases from my experience demonstrating the simplest artifacts in data to the more complex and promiscuous ones.

**About the speaker:** Gershon Celniker is a Data Science manager at Check Point, previously a Principal Data Scientist at Verint and Chief Data Scientist at Wiser. He holds a B.Sc from Technion Institute and a MSc from Hebrew University in Bioinformatics. Currently his main areas of research interest lie in the design of ML and NLP algorithms and their applications in Cybersecurity.

**Video:** TBA

**Slides:** TBA


Asaf Valadarsky - The Many Benefits of Weak Supervision
---------------------------------------------------------------------------
**Speaker:** Asaf Valadarsky

**Title:** The Many Benefits of Weak Supervision

**Abstract:** Today, running ML workloads have a hidden cost which we all know too well - the cost of gaining access to (preferably high quality) tagged data.
For a given classification task, if we really think about it, most of the time we have a heuristic (or several of those) which usually "hits the mark" most of the time -- doctors have a fairly good sense about tumors, keywords in website usually indicate strongly on its content, and hearing a car suddenly break usually means that there is something wrong on the road. What if we could leverage these heuristics to create tagged data? and even more so, what if we could use these heuristics to actually train classifiers without the need of any tagged data at all?

In this talk I will tell you about a new paradigm called "weak supervision" (or "data programming"), allowing you to transform heuristics, in the form of decision functions (be them noisy or even from external sources), into strong classifiers -- thus accelerating research, enabling rapid prototyping, and allowing to match the performance of state-of-the-art models without the need of any tagged data. Besides classical classification, I will also showcase additional interesting use-cases, from bootstrapping chatbots to the automatic design of data-augmentation pipelines.

**About the speaker:** Asaf is currently the lead data-scientist at otonomo where he spends most of his days extracting meaningful insights from car data. He holds a PhD in CS from the Hebrew University.

**Video:** TBA

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_12/The%20Many%20Benefits%20of%20Weak%20Supervision.pdf



DataTalks #13: The Beauty and The Hyperparameter Optimization Beast
=========================================================================

Our 13th meetup was hosted by Wix.com and shared the long journey of discovering an optimal solution for visual beauty evaluation, and gave a sneak peak into a new and innovative package to tune hyperparameters.

**Event page:** https://www.meetup.com/DataHack/events/264038866/


Olha Shainoha - Can Machines Learn Beuty?
-----------------------------------------
**Speaker:** Olha Shainoha

**Title:** Can Machines Learn Beuty?

**Abstract:** How can we objectify beauty? Asking whether an image is beautiful, or how beautiful it is, will probably revoke different responses from different individuals. “Beauty is in the eye of the beholder”, it’s a subjective thing. So, is it possible to teach a machine to make this decision if we humans fail to agree? My answer is - yes. In this talk, I’ll share our journey of discovering an optimal solution for visual beauty evaluation. The transition from Domain experts to Crowdsourcing, from Likert scale to Pairwise comparison, from Ranking to Binary labels, and introduce the final framework we developed based on the acquired knowledge.

**About the speaker:** TBA

**Video:** TBA

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_13/Learning_Beauty.pdf


Gilad Rubin - HyPSTER - HyperParameter Optimization on STERoids
---------------------------------------------------------------
**Speaker:** Gilad Rubin

**Title:** HyPSTER - HyperParameter Optimization on STERoids

**Abstract:** You're a good Data Scientist. You know that you need to work on your data - gathering, exploring, cleaning, processing & validating it. Often times, the best way to evaluate your work is by constructing an ML Pipeline and checking how it performs on various metrics. Since Data Science is in its nature an experimental and iterative process - we need to ask ourselves: How can we choose a proper ML Pipeline efficiently to allow for rapid and continuous improvement on our projects?

What if I told you there was a way to find a simple and accurate ML Pipeline using just a few lines of code with blazing fast performance? Well, dream no more.

Introducing HyPSTER - HyperParameter Optimization on STERoids

HyPSTER is a brand new Python package built on top of Optuna (an awesome Hyperparameter Optimization framework) that helps you find compact and accurate ML Pipelines while staying light and efficient.
HyPSTER uses state of the art algorithms for sampling hyperparameters (e.g. TPE, CMA-ES) and pruning unpromising trials (e.g. Asynchronous Successive Halving), combined with cross-validated early stopping and adaptive learning rates, all packed up in a simple sklearn API that allows for automatic Preprocessing pipeline selection and supports your favorite ML packages (e.g. XGBoost, LightGBM, CatBoost, SGDClassifier) out of the box. And yes, it supports multi CPU/GPU training.

In this talk, I will try to explain the internals of the package and demonstrate its power and simplicity using real-world datasets.

**About the speaker:** Gilad is a data-scientist.

**Video:** TBA

**Slides:** https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_13/HyPSTER.pdf



DataTalks #14: Israeli Elections - Polls, Election Data and Analysis
====================================================================

Our 14th meetup was hosted by Oracle Data Cloud and provided an opportunity to have a glimpse at two fascinating projects which examine past data from Israeli elections!

**Event page:** https://www.meetup.com/DataHack/events/264102560/


Yonatan Lazar-Telem (“AutoPoller”) - How I created and analyzed my transparent poll
-----------------------------------------------------------------------------------
**Speaker:** Yonatan Lazar-Telem

**Title:** How I created and analyzed my transparent poll

**Abstract:** The results of the “Transparent Poll” and its complete data, which was gathered with the help of crowdfunding, were published in April 2019. This data provides a glimpse into the hidden aspects of the polling industry. In this talk, I will present the findings and the questions that arise with regard to the polls that are published in the mainstream media. You are invited to review the “Transparent Poll” data using this link: http://bit.ly/transpolldata

**About the speaker:** Yonatan Lazar-Telem is a data scientist at Mobileye and holds an M.Sc in Statistics from the Hebrew University. Founder of the "AutoPoller" project, which encourages a critical reading of surveys.

**Video:** https://www.youtube.com/watch?v=v5W0GDIr-EI&list=PLZYkt7161wELBhCKNMMthhNo61Z2k8xtu&index=16&t=15s

**Links:** https://shkifut.info/2019/03/transparentpolls/
https://www.facebook.com/AutoPoller/


Itamar Mushkin - Elections results from 1996 to 2019: estimating transition of votes between parties
----------------------------------------------------------------------------------------------------
**Speaker:** Itamar Mushkin

**Title:** Elections results from 1996 to 2019: estimating transition of votes between parties

**Abstract:** We can learn from each parliamentary elections cycle which party gained or lost power (in terms of seats in parliament), but we cannot directly observe transitions between parties. Nevertheless, using the complete voting data gathered in each cycle, we can construct a simple model to answer this and other questions.
In this talk, I will present the underlying model for the transition of votes between parties, its estimations, and the resulting insights. If time permits, I will present additional results from a data-driven analysis of the election outcomes, such as political clusters that emerge from the data. You are invited to review the elections dataset and kernels using this link: https://www.kaggle.com/itamarmushkin/israeli-elections-2015-2013

**About the speaker:**  Itamar Muskhin is a machine learning developer at Precognize, and formerly an Operations Research Analyst at the IAF. He holds a B.Sc and an M.Sc in Physics from the Hebrew University. Likes wrangling data and talking politics, and finds it very time-saving to do both at the same time.

**Video:** https://www.youtube.com/watch?v=CX466Xamlvk&list=PLZYkt7161wELBhCKNMMthhNo61Z2k8xtu&index=17&t=1s



DataTalks #15: Deep Learning for AV Domain Adaptation and Transforming 2D to 3D
===============================================================================

Our 15th meetup was hosted by Innoviz and explored the power of 3D models - be it in autonomous vehicles or how you can generate such models from 2D images!

**Event page:** https://www.meetup.com/DataHack/events/264285462/


Peter Naftaliev - Transforming 2D Images to 3D models
-----------------------------------------------------
**Speaker:** Peter Naftaliev

**Title:** Transforming 2D Images to 3D models

**Abstract:** Technological advances in artificial intelligence allow to take photos of real life objects and automatically create 3D models out of them. This is going to change the way a 3D designer works, allowing for much more efficiency and time saving.

In this talk I will present a new neural network which takes as input a 2D image and automatically a 3D model, using an encoding-decoding architecture. A ResNet based encoder is trained to encode the image into a z-vector with inherent 3D features and a decoder which is actually a boolean classifier is trained to create a 3D model from the z-vector. The reconstruction can happen in any voxel resolution, without retraining the network. Also we will discuss some of the challenges with 3D modelling and ML, we will present cool implementations of ML in the visualization, texture analysis, 3D modeling and other relevant subjects.

**About the speaker:** BSc statistics and operational research. In his previous startup – LipSight – Lipreading software to transcribe voiceless video. Currently runs a ML consultancy and projects group. Part of his work is around creating technologies for 3D modelling using machine learning.


Raja Giryes - Domain Adaptation for Autonomous Vehicles and 3D Data
-------------------------------------------------------------------
**Speaker:** Raja Giryes

**Title:** Domain Adaptation for Autonomous Vehicles and 3D Data

**Abstract:** In this talk, we will survey recent developments in domain adaptation and transfer learning for neural networks training. In particular, we will focus on their usage with 3D and autonomous driving data, where less annotated data is available and therefore they are of great importance.

**About the speaker:**  Raja Giryes is a senior lecturer in the school of electrical engineering at Tel Aviv University. His research interests lie at the intersection between signal and image processing and machine learning, and in particular, in deep learning, inverse problems, sparse representations, and signal and image modeling. He serves as a consultant in various high-tech companies including Innoviz technologies.



DataTalks #29: Distilling BNNs with GANs and StarNet ⚗️🔫⭐️
=========================================================

Our 29th DataTalks meetup was held online and featured talks on distilling BNNs with GANs and StarNet.

**Event page:** https://www.meetup.com/DataHack/events/271491125/


Natan Katz - Distilling BNNs with GANs
--------------------------------------
**Speaker:** Natan Katz, NICE

**Title:** Distilling BNNs with GANs

**Abstract:** In this talk I will go over an interesting ICML 2018 paper that proposes a framework for distilling BNNs using GANs:

Bayesian neural networks (BNNs) allow us to reason about uncertainty in a principled way. Stochastic Gradient Langevin Dynamics (SGLD) enables efficient BNN learning by drawing samples from the BNN posterior using mini-batches. However, SGLD and its extensions require storage of many copies of the model parameters, a potentially prohibitive cost, especially for large neural networks.

We propose a framework, Adversarial Posterior Distillation, to distill the SGLD samples using a Generative Adversarial Network (GAN). At test-time, samples are generated by the GAN. We show that this distillation framework incurs no loss in performance on recent BNN applications including anomaly detection, active learning, and defense against adversarial attacks.

By construction, our framework not only distills the Bayesian predictive distribution, but the posterior itself. This allows one to compute quantities such as the approximate model variance, which is useful in downstream tasks. To our knowledge, these are the first results applying MCMC-based BNNs to the aforementioned downstream applications.

**Paper link:** https://arxiv.org/abs/1806.10317

**About the speaker:** Natan is a Principal Researcher and Research Leader at NICE. He has over 15 years of experience as an algorithm researcher, data scientist, and a research leader in a variety of domains such as: Speech, NLP, quantitative analysis and risks.

**Video:** TBA

**Slides:** `Natan Katz - Distilling BNNs with GANs.pptx <https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_29/%F0%9D%97%A1%F0%9D%97%AE%F0%9D%98%81%F0%9D%97%AE%F0%9D%97%BB%20%F0%9D%97%9E%F0%9D%97%AE%F0%9D%98%81%F0%9D%98%87%20-%20%F0%9D%97%97%F0%9D%97%B6%F0%9D%98%80%F0%9D%98%81%F0%9D%97%B6%F0%9D%97%B9%F0%9D%97%B9%F0%9D%97%B6%F0%9D%97%BB%F0%9D%97%B4%20%F0%9D%97%95%F0%9D%97%A1%F0%9D%97%A1%F0%9D%98%80%20%F0%9D%98%84%F0%9D%97%B6%F0%9D%98%81%F0%9D%97%B5%20%F0%9D%97%9A%F0%9D%97%94%F0%9D%97%A1%F0%9D%98%80.pptx?raw=true>`_


Leonid Karlinsky - Few-Shot Learning for Classification with StarNet
--------------------------------------------------------------------
**Speaker:** Leonid Karlinsky, IBM

**Title:** Few-Shot Learning for Classification with StarNet

**Abstract:** Few-shot learning for classification has advanced significantly in recent years. Yet, these approaches rarely provide interpretability related to their decisions or localization of objects in the scene. In this paper, we introduce StarNet, featuring an end-to-end differentiable non-parametric star-model classification head. Through this head, the backbone is meta-trained using only image-level labels to produce good features for classifying previously unseen categories of few-shot test tasks using a star-model that geometrically matches between the query and support images. This also results in localization of corresponding object instances (on the query and best matching support images), providing plausible explanations for StarNet’s class predictions.

We evaluate StarNet on multiple few-shot classification benchmarks attaining significant gains on CUB and ImageNetLOC-FS. In addition, we test the proposed approach on the previously unexplored and challenging task of Weakly Supervised Few-Shot Object Detection (WS-FSOD), obtaining significant improvements over the baselines.

**Paper link:** https://arxiv.org/abs/2003.06798

**About the speaker:** Leonid Karlinsky leads the CV & DL research team in the Computer Vision and Augmented Reality (CVAR) group @ IBM Research AI. His recent research is in the areas of few-shot learning with specific focus on object detection, metric learning, and example synthesis methods. He received his PhD degree at the Weizmann Institute of Science, supervised by Prof. Shimon Ullman.

**Video:** TBA

**Slides:** `Leonid Karlinsky - Few-Shot Learning for Classification with StarNet.pptx <https://github.com/DataHackIL/DataTalks/blob/master/DataTalks_29/Leonid%20Karlinsky%20-%20Few-Shot%20Learning%20for%20Classification%20with%20StarNet.pptx?raw=true>`_

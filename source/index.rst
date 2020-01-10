.. Geo-Python documentation master file, created by
   sphinx-quickstart on Thu Aug 23 14:00:02 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. figure:: img/banner/GeoPython_banner.png

Welcome to COMP 590 Data Science for Earth, Spring 2020!
========================================================

This course will introduce the tools of data science and machine learning for analysing the earth and its natural and human systems. 

Course format
-------------

This course will have two concurrent goals:  1)  introduce students to the tools of data science and basic machine learning (identifying and processing data, cleaning and preparing data for analysis, setting up problems including supervised/unsupervised learning, regression, and classification, optimization and hyperparameter analysis, and specific techniques such as random forest, gradient boosting and neural networks. And  2) introduce students to the analysis of geospatial data sets, with an introduction to satellite data products (Landsat, Sentinel, GOES, etc.), compute platforms such as Google Earth Engine and Microsoft Azure, and data frameworks such as Xarray and pandas. We will use scientific python (Jupyter Notebooks mainly) and introduce students to these tools at a basic level.

Schedule
--------

We will meet every Monday from 1:25-4:25

.. list-table:: ''
   :widths: 5 10
   :header-rows: 1

   * - Week
     - Topics
   * - 1/13
     - Course Introductions:
         * Intro to data science
         * Intro to geospatial data
         * Form groups by interest area
   * - 1/27
     - Exploring data:
         * Pandas for tabular data, time-series
         * Matplotlib for plotting and visualization
         * Group presentations
   * - 2/3
     - Geospatial visualization:
         * Xarray
         * Cartopy
         * Google Earth Engine
         * Group presentations
   * - 2/10
     - Intro to machine learning:
         * Supervised learning: train/test concept
         * Classification and regression
         * Optimization, gradient descent
         * Scikit-learn
         * Group presentations
   * - 2/17
     - Machine learning:
         * Bias-variance tradeoff and over-fitting
         * Regularization
         * Example: logistic regression
         * Scikit-learn
         * Group presentations
   * - 2/24
     - Machine learning alorithms I:
         * Random forest
         * Feature importance
         * Group presentations
   * - 3/2
     - Machine learning algoriths II:
         * XGBoost
         * Group presentations
   * - 3/16
     - Intro to neural networks:
         * Convolutional neural nets
         * Imagenet, Res-nets
         * Group presentations
   * - 3/23
     - Neural nets continued:
         * Deep learning
         * Group presentations
   * - 3/30
     - Unsupervised learning:
         * Generative Adversarial Networks (GANs)
         * Group presentations
   * - 4/6
     - GANs continued:
         * CycleGAN
         * BigGAN
         * Group presentations
   * - 4/13
     - TBA:
         * Group presentations
   * - 4/20
     - TBA:
         * Peer review papers
   * - 4/30
     - Final group presentations

   
     

.. admonition:: Open Access!

    The course is **open for everyone**. The aim of this course is to share the knowledge and help people to get started with their journey for doing science more efficiently and in a reproducible manner
    using Python programming.

.. admonition:: Step by step instructions with cloud computing!

    The materials are written in a way that you can follow them step by step exactly as they are written, as long as you use the cloud computing resources that
    we provide for you (namely JupyterLab Notebooks using Binder or CSC Cloud computing resources). Read more about our cloud computing environment from :doc:`here <lessons/L1/course-environment-components>`.
    If you work from your own computer, **you need to adjust the file paths to the data** accordingly.

.. toctree::
    :maxdepth: 2
    :caption: Course information

    course-info/course-info
    course-info/learning-goals
    course-info/grading
    course-info/installing-anacondas
    course-info/python-vocabulary
    course-info/resources
    course-info/licensing

.. toctree::
    :maxdepth: 2
    :caption: Lesson 1

    lessons/L1/motivation
    lessons/L1/overview
    lessons/L1/course-environment-components
    lessons/L1/slack-usage
    notebooks/L1/a-taste-of-python.ipynb
    notebooks/L1/gcp-1-variable-naming.ipynb
    lessons/L1/exercise-1

.. toctree::
    :maxdepth: 2
    :caption: Lesson 2

    lessons/L2/overview
    notebooks/L2/Python-basic-elements.ipynb
    notebooks/L2/gcp-2-describing-code.ipynb
    lessons/L2/intro-to-GitHub
    lessons/L2/git-basics
    lessons/L2/GitHub-classroom
    lessons/L2/exercise-2

.. toctree::
   :maxdepth: 2
   :caption: Lesson 3

   lessons/L3/overview
   notebooks/L3/for-loops.ipynb
   notebooks/L3/conditional-statements.ipynb
   notebooks/L3/gcp-3-pep8.ipynb
   lessons/L3/exercise-3

.. toctree::
    :maxdepth: 2
    :caption: Lesson 4

    lessons/L4/overview
    notebooks/L4/functions.ipynb
    notebooks/L4/modules.ipynb
    notebooks/L4/writing-scripts.ipynb
    lessons/L4/exercise-4

.. toctree::
    :maxdepth: 2
    :caption: Lesson 5

    lessons/L5/overview
    lessons/L5/pandas-overview.rst
    notebooks/L5/exploring-data-using-pandas.ipynb
    notebooks/L5/processing-data-with-pandas.ipynb
    lessons/L5/exercise-5

.. toctree::
    :maxdepth: 2
    :caption: Lesson 6

    lessons/L6/overview
    notebooks/L6/advanced-data-processing-with-pandas.ipynb
    notebooks/L6/errors.ipynb
    notebooks/L6/gcp-assertions.ipynb
    notebooks/L6/debugging.ipynb
    lessons/L6/exercise-6

.. toctree::
    :maxdepth: 2
    :caption: Lesson 7

    lessons/L7/overview
    lessons/L7/python-plotting
    lessons/L7/plot-anatomy
    notebooks/L7/matplotlib.ipynb
    notebooks/L7/advanced-plotting.ipynb
    lessons/L7/exercise-7

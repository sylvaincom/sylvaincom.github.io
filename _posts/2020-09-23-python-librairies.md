---
layout: post
title: "Python libraries for Data Scientists"
date: 2020-09-23
---

In this post, I suggest some open-source Python libraries for Data Scientists. I would like to thank Kasra Mansouri and Robin Doumerc for their advice.

**Table of Contents:**
- [For Machine Learning in general](#main)
- [For Machine Learning Operations / industrialization](#indus)
- [For data visualization](#viz)
- [For model interpretation](#interpret)
- [For time series](#ts)

<a name='main'></a>
#### For Machine Learning in general
* [NumPy](https://www.numpy.org){:target="_blank"} by Travis Oliphant: "The fundamental package for scientific computing with Python".<br/>
GitHub repository [here](https://github.com/numpy/numpy){:target="_blank"}.
* [Pandas](https://pandas.pydata.org){:target="_blank"} by Wes McKinney: "Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more."<br/>
GitHub repository [here](https://github.com/pandas-dev/pandas){:target="_blank"}.
* [PyTorch](https://pytorch.org){:target="_blank"} by Facebook: "An open source machine learning framework that accelerates the path from research prototyping to production deployment."<br/>
GitHub repository [here](https://github.com/pytorch/pytorch){:target="_blank"}.
* [scikit-learn](https://scikit-learn.org/stable/){:target="_blank"} by Inria: "Machine Learning in Python. Simple and efficient tools for data mining and data analysis. Accessible to everybody, and reusable in various contexts. Built on NumPy, SciPy, and matplotlib. Open source, commercially usable - BSD license."<br/>
GitHub repository [here](https://github.com/scikit-learn/scikit-learn){:target="_blank"}.
* [SciPy](https://scipy.org/scipylib/){:target="_blank"}: "The SciPy library is one of the core packages that make up the SciPy stack. It provides many user-friendly and efficient numerical routines, such as routines for numerical integration, interpolation, optimization, linear algebra, and statistics."<br/>
GitHub repository [here](https://github.com/scipy/scipy/){:target="_blank"}.
* [TensorFlow](https://www.tensorflow.org){:target="_blank"} by Google: "TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications."<br/>
GitHub repository [here](https://github.com/tensorflow/tensorflow){:target="_blank"}.
<!-- * * [Theano](http://www.deeplearning.net/software/theano/){:target="_blank"} by University of Montreal: "Theano is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently. It can use GPUs and perform efficient symbolic differentiation." -->

[TensorFlow or PyTorch?](https://thegradient.pub/state-of-ml-frameworks-2019-pytorch-dominates-research-tensorflow-dominates-industry/){:target="_blank"} In Oct. 2019, _The Gradient_ compared references to both in public sources over the past year and found PyTorch to be more popular in the research community, while TensorFlow dominates in industry.

<a name='indus'></a>
#### For Machine Learning Operations / industrialization
* [Airflow](https://airflow.apache.org/){:target="_blank"} by Apache: "Airflow is a platform created by the community to programmatically author, schedule and monitor workflows."<br/>
GitHub repository [here](https://github.com/apache/airflow){:target="_blank"}.
* [creme](https://creme-ml.github.io/){:target="_blank"}: "creme is a Python library for online machine learning. All the tools in the library can be updated with a single observation at a time, and can therefore be used to learn from streaming data."<br/>
GitHub repository [here](https://github.com/creme-ml/creme){:target="_blank"}.
* [Dask](https://dask.org/){:target="_blank"}: "Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love".<br/>
GitHub repository [here](https://github.com/dask/dask){:target="_blank"}.
* [Kedro](https://kedro.readthedocs.io/en/stable/){:target="_blank"} by QuantumBlack Labs: "Kedro is an open-source Python framework that applies software engineering best-practice to data and machine-learning pipelines."<br/>
GitHub repository [here](https://github.com/quantumblacklabs/kedro){:target="_blank"}.
* [MLflow](https://mlflow.org/){:target="_blank"}: "An open source platform for the machine learning lifecycle."<br/>
GitHub repository [here](https://github.com/mlflow/mlflow/){:target="_blank"}.
* [Prefect](https://www.prefect.io/){:target="_blank"}: "The easiest way to automate your data".<br/>
GitHub repository [here](https://github.com/PrefectHQ/prefect){:target="_blank"}.
* [Steamlit](https://www.streamlit.io/){:target="_blank"}: "Streamlit’s open-source app framework is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!  All in pure Python. All for free."<br/>
GitHub repository [here](https://github.com/streamlit/streamlit){:target="_blank"}.

<a name='viz'></a>
#### For data visualization
* [Matplotlib](https://matplotlib.org/){:target="_blank"}: "Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python."<br/>
GitHub repository [here](https://github.com/matplotlib/matplotlib){:target="_blank"}.
* [Plotly](https://plotly.com/python/){:target="_blank"}: "Plotly's Python graphing library makes interactive, publication-quality graphs. Examples of how to make line plots, scatter plots, area charts, bar charts, error bars, box plots, histograms, heatmaps, subplots, multiple-axes, polar charts, and bubble charts."<br/>
GitHub repository [here](https://github.com/plotly/plotly.py){:target="_blank"}.
* [seaborn](https://seaborn.pydata.org/){:target="_blank"} by Michael Waskom: "Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics."<br/>
GitHub repository [here](https://github.com/plotly/plotly.py){:target="_blank"}.
* [umap-learn](https://umap-learn.readthedocs.io/en/latest/){:target="_blank"} by Leland McInnes: "Uniform Manifold Approximation and Projection (UMAP) is a dimension reduction technique that can be used for visualisation similarly to t-SNE, but also for general non-linear dimension reduction."<br/>
GitHub repository [here](https://github.com/lmcinnes/umap){:target="_blank"}.

<a name='interpret'></a>
#### For model interpretation
* [dtreeviz](https://github.com/parrt/dtreeviz){:target="_blank"} by Terence Parr and Prince Grover: "A python library for decision tree visualization and model interpretation."<br/>
GitHub repository [here](https://github.com/parrt/dtreeviz){:target="_blank"}.
* [shap](https://github.com/slundberg/shap){:target="_blank"} by Scott Lundberg: "SHAP (SHapley Additive exPlanations) is a game theoretic approach to explain the output of any machine learning model."<br/>
GitHub repository [here](https://github.com/slundberg/shap){:target="_blank"}.


<a name='ts'></a>
#### For time series

I highly suggest having a look at [Time Series Forecasting Best Practices & Examples](https://microsoft.github.io/forecasting/){:target="_blank"} by Microsoft and [Time series related software](https://github.com/alan-turing-institute/sktime/wiki/related-software){:target="_blank"} by The Alan Turing Institute.

* [Anomaly Detection Toolkit (ADTK)](https://adtk.readthedocs.io/en/stable/){:target="_blank"} by Arundo Analytics: "Anomaly Detection Toolkit (ADTK) is a Python package for unsupervised / rule-based time series anomaly detection."<br/>
GitHub repository [here](https://github.com/arundo/adtk){:target="_blank"}.
* [darts](https://unit8co.github.io/darts/){:target="_blank"} by Unit8: "darts is a python library for easy manipulation and forecasting of time series. It contains a variety of models, from classics such as ARIMA to neural networks. The models can all be used in the same way, using fit() and predict() functions, similar to scikit-learn."<br/>
GitHub repository [here](https://github.com/unit8co/darts){:target="_blank"}.
* [GluonTS](https://gluon-ts.mxnet.io/){:target="_blank"} by Amazon Web Services: "Gluon Time Series (GluonTS) is the Gluon toolkit for probabilistic time series modeling, focusing on deep learning-based models."<br/>
GitHub repository [here](https://github.com/awslabs/gluon-ts){:target="_blank"}.
* [pmdarima](https://alkaline-ml.com/pmdarima/){:target="_blank"} by Taylor G Smith: "pmdarima brings R’s beloved auto.arima to Python, making an even stronger case for why you don’t need R for data science. pmdarima is 100% Python + Cython and does not leverage any R code, and implements a single, easy-to-use scikit-learn-esque estimator."<br/>
GitHub repository [here](https://github.com/alkaline-ml/pmdarima){:target="_blank"}.
* [Prophet](https://facebook.github.io/prophet/){:target="_blank"} by Facebook: "Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth."<br/>
GitHub repository [here](https://github.com/facebook/prophet){:target="_blank"}.
<!--* * [PyTorch Forecasting](https://pytorch-forecasting.readthedocs.io/en/latest/){:target="_blank"}: "Pytorch Forecasting aims to ease timeseries forecasting with neural networks for both real-world cases and research alike."<br/>
GitHub repository [here](https://github.com/jdb78/pytorch-forecasting){:target="_blank"}. -->
* [pyts](https://pyts.readthedocs.io/en/stable/){:target="_blank"} by Johann Faouzi: "pyts is a Python package dedicated to time series classification."<br/>
GitHub repository [here](https://github.com/johannfaouzi/pyts){:target="_blank"}.
* [ruptures](https://centre-borelli.github.io/ruptures-docs/){:target="_blank"} by Charles Truong, Laurent Oudre and Nicolas Vayatis: "ruptures is designed to perform offline change point algorithms within the Python language."<br/>
GitHub repository [here](https://github.com/deepcharles/ruptures){:target="_blank"}.
* [sktime](https://www.sktime.org/en/latest/#){:target="_blank"} by The Alan Turing Institute: "sktime is a Python machine learning toolbox for time series with a unified interface for multiple learning tasks. We currently support: Forecasting, Time series classification, and Time series regression.
sktime provides dedicated time series algorithms and scikit-learn compatible tools for building, tuning, and evaluating composite models.
For deep learning methods, see our companion package: [sktime-dl](https://github.com/sktime/sktime-dl){:target="_blank"}."<br/>
GitHub repository [here](https://github.com/alan-turing-institute/sktime){:target="_blank"}.
* [statsmodels](https://www.statsmodels.org/devel/){:target="_blank"} by Skipper Seabold and Josef Perktold: "statsmodels is a Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration. An extensive list of result statistics are available for each estimator."<br/>
GitHub repository [here](https://github.com/statsmodels/statsmodels){:target="_blank"}.
* [tsfresh](https://tsfresh.readthedocs.io/en/latest/){:target="_blank"} by Blue Yonder: TSFRESH stands for "Time Series Feature extraction based on scalable hypothesis tests". "The package contains many feature extraction methods and a robust feature selection algorithm."<br/>
GitHub repository [here](https://github.com/blue-yonder/tsfresh){:target="_blank"}.
* [tslearn](https://tslearn.readthedocs.io/en/stable/){:target="_blank"} by Romain Tavenard: "tslearn is a Python package that provides machine learning tools for the analysis of time series. This package builds on (and hence depends on) scikit-learn, numpy and scipy libraries."<br/>
GitHub repository [here](https://github.com/tslearn-team/tslearn){:target="_blank"}.
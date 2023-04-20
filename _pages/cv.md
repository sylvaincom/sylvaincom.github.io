---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* [École Normale Supérieure Paris-Saclay](https://en.wikipedia.org/wiki/%C3%89cole_normale_sup%C3%A9rieure_Paris-Saclay), *Doctor of Philosophy - PhD*, Paris Area, 2020 &ndash; 2023
  * Mathematics / Data Science applied to time series, at the [Centre Borelli](https://centreborelli.ens-paris-saclay.fr/en).
  * Topic: Symbolic representation for physiological signals.
  * Advisors: [Laurent Oudre](http://www.laurentoudre.fr/) and [Charles Truong](https://charles.doffy.net/).
  * Co-organizer of the _Machine Learning and Massive Data Analysis (MLMDA)_ weekly seminars.
  * Supervision of a research internship for a normalien student from the Mathematics Department (Mar. - June 2022).
  * Tutor of students from the Master 2 MVA (2020-21).
* [École des Mines de Nancy](https://en.wikipedia.org/wiki/%C3%89cole_nationale_sup%C3%A9rieure_des_mines_de_Nancy), *Master of Science*, Nancy, 2017 &ndash; 2020
  * Big Data & Data Science track within the Department of Mathematical Engineering.
  * Top of the class in the final-year. Awarded the Saint-Gobain Research Excellence Scholarship 2020 for academic achievements
  * Relevant courses in Mathematics: Deep learning, Information theory, Machine learning, Operations research, Optimization, Probabilities, Statistics, Stochastic modelling, Time series.
  * Programming: Python, R, MATLAB, C/C++.
* [Lycée Louis-le-Grand](https://en.wikipedia.org/wiki/Lyc%C3%A9e_Louis-le-Grand), _Classe Préparatoire aux Grandes Écoles_, Paris, 2014 &ndash; 2017
  * Intensive preparation for the highly selective entrance examination to the _Grandes Écoles_ (leading national French schools of Engineering).
  * _Filière PCSI/PC*_: Advanced Mathematics, Physics, Chemistry, Philosophy and English.
* [Lycée Louis-le-Grand](https://en.wikipedia.org/wiki/Lyc%C3%A9e_Louis-le-Grand), _Baccalauréat général avec la mention très bien_, Paris, 2011 &ndash; 2014
  * At the end of high school, I received the _Baccalauréat_ (main French diploma required to pursue university studies) in Science with Highest Honors.

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional experience
======
* *Data Scientist intern*, [Artefact](https://www.artefact.com), Paris, Mar. 2020 &ndash; Aug. 2020 (6 months).
  * Consulting for a major player in the food industry: demand sensing for new products with very few historical sales data (« cold start »).
  * Involved throughout the whole pipeline in agile development: exploratory data analysis, model iteration, production, industrialisation, and delivery.
  * Technologies: AWS, Dask, Docker, Git, Pandas, Prophet, Unix, scikit-learn, statsmodels, tslearn.
  * Result: The method developed for a specific country, in pairs with a Senior Data Scientist, was a success and was being deployed in other countries at the end of my internship.
  * Links: [Medium blog](https://medium.com/artefact-engineering-and-data-science/how-did-we-predict-sales-for-products-with-almost-no-historical-data-launches-d116e37eec44).
* *Research Project in Data Science*, [École des Mines de Nancy](https://en.wikipedia.org/wiki/%C3%89cole_nationale_sup%C3%A9rieure_des_mines_de_Nancy), Nancy, Oct. 2019 &ndash; Feb. 2020 (5 months).
  * Topic: Comparison of empirical probability distributions using integral probability metrics and f-divergences.
  * Result: I show that a new simulation method for the Choquet integral is "correct".
  * Links: [report](https://sylvaincom.github.io/files/comparison_distributions_report.pdf) / [slides](https://sylvaincom.github.io/files/comparison_distributions_slides.pdf) / [GitHub](https://github.com/sylvaincom/comparison-distributions).
* *Data Scientist intern*, [Servier](https://en.wikipedia.org/wiki/Laboratoires_Servier), Paris Area, June 2019 &ndash; Sep. 2019 (3 months).
  * Topic: Generating fictitious realistic patient data with generative adversarial networks (GANs).
  * Links: [report](https://sylvaincom.github.io/files/medgan_report.pdf) / [slides](https://sylvaincom.github.io/files/medgan_slides.pdf) / [GitHub](https://github.com/sylvaincom/comparison-distributions) / [Medium blog](https://towardsdatascience.com/a-basic-intro-to-gans-generative-adversarial-networks-c62acbcefff3).
* *Research Project in Data Science*, [Saint-Gobain](https://en.wikipedia.org/wiki/Saint-Gobain), Paris Area, Oct. 2018 &ndash; June 2019 (9 months).
  * Topic: Anomaly detection using principal component analysis (PCA) and Gaussian kernel PCA.
  * Result: the algorithm can detect 100% of the failure days observed by operators from Saint-Gobain.
  * Links: [GitHub](https://github.com/sylvaincom/anomaly-detection-PCA).

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
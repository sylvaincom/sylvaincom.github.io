---
title: "An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals."
collection: preprint
permalink: /publication/2023-10-01-dsymb-icdm
excerpt: 'd_symb symbolic representation and distance measure for multivariate time series.'
date: 2023-10-01
venue: 'Proceedings of the International Conference on Data Mining (AI4TS Workshop)'
paperurl: 'http://www.laurentoudre.fr/publis/ICDM2023.pdf'
citation: 'Sylvain W. Combettes, Charles Truong, and Laurent Oudre. "An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals." In _Proceedings of the International Conference on Data Mining (AI4TS Workshop)_, Shanghai, China, 2023.
---

Links: [paper](http://www.laurentoudre.fr/publis/ICDM2023.pdf) / [code](https://github.com/sylvaincom/d-symb)

Abstract:
>We introduce $d_{symb}$, a novel distance measure for comparing multivariate non-stationary physiological signals. Unlike most distance measures on multivariate signals such as variants of Dynamic Time Warping (DTW), dsymb can take into
account their non-stationarity thanks to a symbolization step. This step is based on a change-point detection procedure, that splits a non-stationary signal into several stationary segments, followed by quantization using $K$-means clustering. The proposed distance measure leverages the general edit distance that is applied to the symbolic sequences. The performance of $d_{symb}$ compared to two commonly used DTW variants is illustrated by applying it to physiological signals recorded during walking protocols. In particular, $d_{symb}$ is shown to be interpretable: its symbolization detects the segments that correspond to salient behaviors. An open source GitHub repository is made available to reproduce all the experiments in Python.
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=yXz3FG8AAAAJ">my Google Scholar profile</a>.

<details>
<summary>Click here for an overview of my research.</summary>
<hr style="height: 3px; background-color: black;">

My PhD research was at the intersection of Mathematics and Machine Learning for time series analysis. More precisely, my publications are on symbolic representations and distances between univariate and multivariate time series. My PhD manuscript <b>[T1]</b> sums up my research and contains 2 literature reviews, 2 major contributions (ASTRIDE <b>[IC3]</b> and $d_{symb}$ <b>[IC1]</b>), 1 interactive tool on Streamlit (the $d_{symb}$ playground <b>[IC2]</b>) and 1 open-access data set (the arm-CODA data set <b>[J1]</b>). The abstract of my manuscript is as follows.
<br><br>

<i>The objectives of this thesis are to define novel symbolic representations and distance measures that are suited for time series that can be multivariate and non-stationary.
In addition, they should preserve the time information, be interpretable, and fast to compute.
We review symbolic representations of time series (that transform a real-valued series into a shorter discrete-valued series), as well as distance measures on time series, strings, and symbolic sequences (that result from a symbolization process).</i><br><br>

<i>We propose two contributions: ASTRIDE for a data set of univariate time series, and $d_{symb}$  for a data set of multivariate time series.
We also developed the $d_{symb}$ playground, an online interactive tool that allows users to apply $d_{symb}$ to their uploaded data.
ASTRIDE and $d_{symb}$ are data-driven as they use change-point detection for the segmentation step, then either quantiles or a $K$-means clustering algorithm for the quantization step.
Finally, they apply the general edit distance with custom costs between the resulting symbolic sequences.</i><br><br>

<i>We show the performance of ASTRIDE compared to 4 other symbolic representations on reconstruction and, when applicable, on classification tasks.
For $d_{symb}$, experiments show how interpretable the symbolization is.
Moreover, compared to 9 elastic distances on a clustering task, $d_{symb}$ achieves a competitive performance while being several orders of magnitude faster.</i>
<hr style="height: 3px; background-color: black;">
</details>

## PhD manuscript

<table>
  <tr>
    <td rowspan="2" style="width: 50px;"><b>T1</b></td>
    <td>Sylvain Combettes. Symbolic representations of time series. Machine Learning [cs.LG]. Université Paris-Saclay, 2024. English. NNT : 2024UPASM002. tel-04573912.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://theses.fr/2024UPASM002">theses.fr</a> / <a href="https://theses.hal.science/tel-04573912">HAL</a> / <a href="https://theses.hal.science/tel-04573912v1/document">manuscript PDF</a> / <a href="/files/2024_01_08_phd_defense.pdf">defense slides PDF</a>.</td>
  </tr>
</table>

## International conference papers

<table>
  <tr>
    <td rowspan="3" style="width: 50px;"><b>IC3</b></td>
    <td>S. W. Combettes, C. Truong, and L. Oudre. "Symbolic representation for time series." To appear in <i>Proceedings of the European Signal Processing Conference (EUSIPCO)</i>, Lyon, France, 2024.</td>
  </tr>
  <tr>
    <td>Method name: ASTRIDE.</td>
  </tr>
  <tr>
    <td>Links: <a href="http://www.laurentoudre.fr/publis/EUSIPCO2024symb.pdf">paper PDF</a> / <a href="https://eusipcolyon.sciencesconf.org/">EUSIPCO 2024</a>.</td>
  </tr>

  <tr>
    <td rowspan="3" style="width: 50px;"><b>IC2</b></td>
    <td>S. W. Combettes, P. Boniol, C. Truong, and L. Oudre. "d_{symb} playground: an interactive tool to explore large multivariate time series datasets." In <i>Proceedings of the International Conference on Data Engineering (ICDE)</i>, Utrecht, Netherlands, 2024.</td>
  </tr>
  <tr>
    <td>Method name: $d_{symb}$ playground.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://icde2024.github.io/demos.html">website</a> / <a href="http://www.laurentoudre.fr/publis/dsymb_demo.pdf">paper PDF</a> / <a href="/files/2024_05_15_dsymb_playground_poster.pdf">poster PDF</a> / <a href="https://github.com/boniolp/dsymb-playground">GitHub</a> / <a href="https://dsymb-playground.streamlit.app/">Streamlit app</a> / <a href="https://youtu.be/4verma-Aqo8">4 min YouTube video</a> / <a href="https://icde2024.github.io/">ICDE 2024</a>.</td>
  </tr>

  <tr>
    <td rowspan="3" style="width: 50px;"><b>IC1</b></td>
    <td>S. W. Combettes, C. Truong, and L. Oudre. "An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals." In <i>Proceedings of the International Conference on Data Mining Workshops (ICDMW)</i>, Shanghai, China, 2023.</td>
  </tr>
  <tr>
    <td>Method name: $d_{symb}$.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://ieeexplore.ieee.org/abstract/document/10411636">website</a> / <a href="http://www.laurentoudre.fr/publis/ICDM2023.pdf">paper PDF</a> / <a href="/files/2023_12_01_dsymb_icdm_slides.pdf">slides PDF</a> / <a href="/files/2023_12_01_dsymb_icdm_poster.pdf">poster PDF</a> / <a href="https://github.com/sylvaincom/d-symb">GitHub</a> / <a href="https://www.cloud-conf.net/icdm2023/index.html">ICDM 2023</a> / <a href="https://ai4ts.github.io/icdm2023">AI4TS workshop</a>.</td>
  </tr>
</table>

## National conference papers

<table>
  <tr>
    <td rowspan="3" style="width: 50px;"><b>NC1</b></td>
    <td>S. W. Combettes, C. Truong, and L. Oudre. "SAX-DD: une nouvelle représentation symbolique pour séries temporelles" In <i>Proceedings of the Groupe de Recherche et d’Etudes En Traitement Du Signal et Des Images (GRETSI)</i>, Nancy, France, 2022.</td>
  </tr>
  <tr>
    <td>Method name: SAX-DD.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://gretsi.fr/data/colloque/pdf/2022_combettes826.pdf">paper PDF</a> / <a href="https://gretsi.fr/colloque2022/">GRETSI 2022</a>.</td>
  </tr>
</table>

## Journal papers

<table>
  <tr>
    <td rowspan="3" style="width: 50px;"><b>J1</b></td>
    <td>S. W. Combettes, P. Boniol, A. Mazarguil, D. Wang, D. Vaquero-Ramos, M. Chauveau, L. Oudre, N. Vayatis, P.-P. Vidal, A. Roren, and M.-M. Lefèvre-Colau. "Arm-CODA: A Data Set of Upper-limb Human Movement During Routine Examination." <i>Image Processing On Line (IPOL)</i>, 14:1-13, 2024.</td>
  </tr>
  <tr>
    <td>Data set name: Arm-CODA.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://www.ipol.im/pub/art/2024/494/">website</a> / <a href="https://www.ipol.im/pub/art/2024/494/article.pdf">paper PDF</a> / <a href="https://ipolcore.ipol.im/demo/clientApp/demo.html?id=494">demo</a>.</td>
  </tr>
</table>

## Preprints

<table>
  <tr>
    <td rowspan="3" style="width: 50px;"><b>PR1</b></td>
    <td>S. W. Combettes, C. Truong, and L. Oudre. "ASTRIDE: Adaptive Symbolization for Time Series Databases." <i>arXiv</i>, abs/2302.04097, 2023.</td>
  </tr>
  <tr>
    <td>Method name: ASTRIDE.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://arxiv.org/abs/2302.04097">website</a> / <a href="https://arxiv.org/pdf/2302.04097.pdf">paper PDF</a> / <a href="https://github.com/sylvaincom/astride">GitHub</a>.</td>
  </tr>
</table>

<!-- <table>
  <tr>
    <th>Year</th>
    <th>Authors</th>
    <th>Title</th>
    <th>Conference / journal</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>2024</td>
    <td>S. W. Combettes, P. Boniol, C. Truong, and L. Oudre</td>
    <td>$d_{symb}$ playground: an interactive tool to explore large multivariate time series datasets</td>
    <td>Proceedings of the International Conference on Data Engineering (ICDE)</td>
    <td>accepted</td>
  </tr>
  <tr>
    <td>2024</td>
    <td>S. W. Combettes, C. Truong, and L. Oudre</td>
    <td>Arm-CODA: A Dataset of Upper-limb Human Movement during Routine Examination</td>
    <td>Image Processing On Line</td>
    <td>published</td>
  </tr>
  <tr>
    <td>2023</td>
    <td>S. W. Combettes, C. Truong, and L. Oudre</td>
    <td>An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals</td>
    <td>Proceedings of the Proceedings of the International Conference on Data Mining Workshops (ICDMW)</td>
    <td>published</td>
  </tr>
  <tr>
    <td>2023</td>
    <td>S. W. Combettes, C. Truong, and L. Oudre</td>
    <td>ASTRIDE: Adaptive Symbolization for Time Series Databases </td>
    <td>arXiv</td>
    <td>preprint</td>
  </tr>
</table> -->


{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

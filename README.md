# Local tree methods for classification: a review and some dead ends
Alice Cleynen, Louis Raynal, Jean-Michel Marin
2023-12-14

### Citation

Alice Cleynen, Louis Raynal and Jean-Michel Marin (December 2023). Local tree methods for classification: a review and some dead ends. Computo.
<https://doi.org/10.57750/3j8m-8d57>

### Badges

[![build and
publish](https://github.com/computorg/published-202312-cleynen-local/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202312-cleynen-local/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202312-cleynen-local/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202312-cleynen-local)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202312-cleynen-local)
[![DOI:10.57750/3j8m-8d57](https://img.shields.io/badge/DOI-10.57750%2F3j8m--8d57-034E79.svg)](https://doi.org/10.57750/3j8m-8d57)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- [Alice Cleynen](https://alice.cleynen.fr/) (IMAG, Univ Montpellier, CNRS, UMR 5149, Montpellier, France)
- Louis Raynal (Centre Hospitalier Départemental Vendée, La Roche-sur-Yon, France)
- [Jean-Michel Marin](https://imag.umontpellier.fr/~marin/) (IMAG, Univ Montpellier, CNRS, UMR 5149, Montpellier, France)

### Abstract

Random Forests (RF) (Breiman 2001) are very popular machine learning
methods. They perform well even with little or no tuning, and have some
theoretical guarantees, especially for sparse problems (Biau 2012;
Scornet et al. 2015). These learning strategies have been used in
several contexts, also outside the field of classification and
regression. To perform Bayesian model selection in the case of
intractable likelihoods, the ABC Random Forests (ABC-RF) strategy of
Pudlo et al. (2016) consists in applying Random Forests on training sets
composed of simulations coming from the Bayesian generative models. The
ABC-RF technique is based on an underlying RF for which the training and
prediction phases are separated. The training phase does not take into
account the data to be predicted. This seems to be suboptimal as in the
ABC framework only one observation is of interest for the prediction. In
this paper, we study tree-based methods that are built to predict a
specific instance in a classification setting. This type of methods
falls within the scope of local (lazy/instance-based/case specific)
classification learning. We review some existing strategies and propose
two new ones. The first consists in modifying the tree splitting rule by
using kernels, the second in using a first RF to compute some local
variable importance that is used to train a second, more local, RF.
Unfortunately, these approaches, although interesting, do not provide
conclusive results.

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-biau:2012" class="csl-entry">

Biau, G. 2012. “Analysis of a Random Forest Model.” *Journal of Machine
Learning Research* 13: 1063–95.

</div>

<div id="ref-breiman:2001" class="csl-entry">

Breiman, L. 2001. “Random Forests.” *Machine Learning* 45: 5–32.

</div>

<div id="ref-pudlo:etal:2016" class="csl-entry">

Pudlo, P., J.-M. Marin, A. Estoup, J.-M. Cornuet, M. Gautier, and C. P.
Robert. 2016. “Reliable ABC Model Choice via Random Forests.”
*Bioinformatics* 32 (6): 859–66.

</div>

<div id="ref-scornet:etal:2015" class="csl-entry">

Scornet, E., G. Biau, and J.-P. Vert. 2015. “Consistency of Random
Forests.” *Annals of Statistics* 43 (4): 1716–41.

</div>

</div>

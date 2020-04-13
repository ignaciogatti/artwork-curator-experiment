# artwork-curator-experiment


This repository contains the reproducibility kit for a couple of experiments that we use to validate our approach. The details of the approach are available [here](https://github.com/ignaciogatti/artwork-retrieval-api).

Each notebook has the code to reproduce an experiment

## Agree/Disagree distribution

Agree distribution notebook allows us to analyse the distribution of hits and mistakes that achieved each approach for a given reference artwork.


<p align="center">
  <img src="https://github.com/ignaciogatti/artwork-curator-experiment/blob/master/plots/encode_agree_dist_7066.png" width="500" height="500">

  <img src="https://github.com/ignaciogatti/artwork-curator-experiment/blob/master/plots/social_graph_agree_dist_7066.png" width="500" height="500">
</p>

## Fleiss Kappa coefficient

Fleiss Kappa anlysis notebook processes the raw data in order to obtain a valid input to compute the [Fleiss Kappa coefficient](https://en.wikipedia.org/wiki/Fleiss%27_kappa)


<p align="center">
  <img src="https://github.com/ignaciogatti/artwork-curator-experiment/blob/master/plots/encode_fleiss.png" width="500" height="500">

  <img src="https://github.com/ignaciogatti/artwork-curator-experiment/blob/master/plots/social_graph_fleiss.png" width="500" height="500">
</p>

## Precission@k

Precision plot notebook processes the raw data in order to compute the [Precission@k](https://medium.com/@m_n_malaeb/recall-and-precision-at-k-for-recommender-systems-618483226c54) metric for each approach.


<p align="center">
  <img src="https://github.com/ignaciogatti/artwork-curator-experiment/blob/master/plots/precision_k.png" width="500" height="500">
</p>

## Style and genre distribution

AVA-distribution-recommended-set processes the recommended set obtained for each approach in order to analyse the [diversity](https://towardsdatascience.com/frontiers-of-recommendation-systems-diversity-f668adad502c) of each set.


<p align="center">
  <img src="https://github.com/ignaciogatti/artwork-curator-experiment/blob/master/plots/style_genre_specialization.png" width="500" height="500">

  <img src="https://github.com/ignaciogatti/artwork-curator-experiment/blob/master/plots/style_genre_diversity.png" width="500" height="500">
</p>

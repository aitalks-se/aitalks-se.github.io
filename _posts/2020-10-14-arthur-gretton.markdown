---
layout: post
speaker:  "Arthur Gretton"
title: "Critics for generative adversarial networks: results and conjectures"
date:   2020-10-14 13:00:00 +0100
categories: aitalks
image: assets/speakers/gretton.jpg
slides: https://www.chalmers.se/SiteCollectionDocuments/Centrum/CHAIR/AI%20Talks/chalmers20_gretton.pdf
recording: https://youtu.be/8HPhDHzCQs0
blurb: >-
  Arthur Gretton is Professor with the Gatsby Computational Neuroscience Unit, and director of the Centre for Computational Statistics and Machine Learning at UCL. His research interests include the design and training of generative models, both implicit (e.g. GANs) and explicit (high/infinite dimensional exponential family models), nonparametric hypothesis testing, and kernel methods.
---

## Critics for generative adversarial networks: results and conjectures

### Abstract
Generative adversarial networks (GANs) use neural networks as generative models, creating realistic images that mimic real-life reference samples (for instance, images of faces, bedrooms, and more). These networks require an adaptive critic function while training, to teach the generator network how to improve its performance. To achieve this, the critic needs to measure how close generated samples are to true samples, and to provide a useful gradient signal the generator network.

I will explore the design of critic functions for GANs, including f-divergences as used in the original GAN design, and integral probability metrics (such as the Maximum Mean Discrepancy) as used in later GANs. I will provide some observations and conjectures on critic design: in particular, a problem-specific critic seems to be helpful, and the critic needs to be deliberately weakened to ensure good GAN performance.

### About the speaker
![Arthur Gretton](/assets/speakers/gretton.jpg){:class="post-speaker-image"}
Arthur Gretton is a Professor with the Gatsby Computational Neuroscience Unit, and director of the Centre for Computational Statistics and Machine Learning (CSML) at UCL. He received degrees in Physics and Systems Engineering from the Australian National University, and a PhD with Microsoft Research and the Signal Processing and Communications Laboratory at the University of Cambridge. He previously worked at the MPI for Biological Cybernetics, and at the Machine Learning Department, Carnegie Mellon University.

Arthur's recent research interests in machine learning include the design and training of generative models, both implicit (e.g. GANs) and explicit (high/infinite dimensional exponential family models), nonparametric hypothesis testing, and kernel methods.

He has been an associate editor at IEEE Transactions on Pattern Analysis and Machine Intelligence from 2009 to 2013, an Action Editor for JMLR since April 2013, an Area Chair for NeurIPS in 2008 and 2009, a Senior Area Chair for NeurIPS in 2018, an Area Chair for ICML in 2011 and 2012, a member of the COLT Program Committee in 2013, and a member of Royal Statistical Society Research Section Committee since January 2020. Arthur was program co-chair for AISTATS in 2016, tutorials co-chair for ICML 2018, workshops co-chair for ICML 2019, program co-chair for the Dali workshop in 2019, and co-organsier of the Machine Learning Summer School 2019 in London.

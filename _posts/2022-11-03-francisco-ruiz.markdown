---
layout: post
title:  "Francisco J. R. Ruiz"
talk: "Discovering novel algorithms with AlphaTensor"
date:   2022-11-03 10:00:00 +0100
datenotset: false
host: Lennart Svensson
host-url: https://www.chalmers.se/en/staff/Pages/lennart-svensson.aspx
categories: aitalks
location: ED (Chalmers) & Zoom
zoom: https://ui.ungpd.com/Surveys/0649eac3-12ec-4d41-a640-d20a7d4e82f7
image: assets/speakers/ruiz.jpeg
blurb: >-
  Francisco J. R. Ruiz is a Research Scientist working at DeepMind in the Deep Learning Team. His research is focused on probabilistic modeling and inference, generative models, and applications of machine learning in mathematics.
---

## Discovering novel algorithms with AlphaTensor

### Abstract
Improving the efficiency of algorithms for fundamental computations can have a widespread impact, as it can affect the overall speed of a large amount of computations. Matrix multiplication is one such primitive task, occurring in many systems—from neural networks to scientific computing routines. The automatic discovery of algorithms using machine learning offers the prospect of reaching beyond human intuition and outperforming the current best human-designed algorithms. However, automating the algorithm discovery procedure is intricate, as the space of possible algorithms is enormous. Here we report a deep reinforcement learning approach based on AlphaZero1 for discovering efficient and provably correct algorithms for the multiplication of arbitrary matrices. Our agent, AlphaTensor, is trained to play a single-player game where the objective is finding tensor decompositions within a finite factor space. AlphaTensor discovered algorithms that outperform the state-of-the-art complexity for many matrix sizes. Particularly relevant is the case of 4 × 4 matrices in a finite field, where AlphaTensor’s algorithm improves on Strassen’s two-level algorithm for the first time, to our knowledge, since its discovery 50 years ago2. We further showcase the flexibility of AlphaTensor through different use-cases: algorithms with state-of-the-art complexity for structured matrix multiplication and improved practical efficiency by optimizing matrix multiplication for runtime on specific hardware. Our results highlight AlphaTensor’s ability to accelerate the process of algorithmic discovery on a range of problems, and to optimize for different criteria.

### About the speaker
![ Francisco J. R. Ruiz](/assets/speakers/ruiz.jpeg){:class="post-speaker-image"}  Francisco J. R. Ruiz is a Research Scientist working at DeepMind in the Deep Learning Team. His research is focused on probabilistic modeling and inference, generative models, and applications of machine learning in mathematics. Before joining DeepMind, he was a Postdoctoral Research Scientist in the Department of Computer Science at Columbia University and in the Engineering Department at the University of Cambridge, where he held a Marie-Sklodowska Curie fellowship in the context of the E.U. Horizon 2020 program. He completed his Ph.D. and M.Sc. from the University Carlos III in Madrid.

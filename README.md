### Hi, I'm Alex 👋

I'm a PhD student in the University of Wisconsin-Madison statistics program. My github is a mixture of research code, #rstats ✨ contributions, and personal data analysis projects. I write long-form explainers on my blog, https://www.alexpghayes.com/. At the moment most of my energy goes to research.

## Research & research code

I study community detection in networks with [Karl Rohe](http://pages.stat.wisc.edu/~karlrohe/homepage/Welcome.html), primarily using spectral methods. My research code is all in R at the moment, and none of it is on CRAN, primarily because my research packages are only about 75 percent done; the key functionality works but documentation, tests, and other user-friendly elements may be missing.

- [`aPPR`](https://rohelab.github.io/aPPR/) helps you calculate approximate personalized pageranks from large graphs, including those that can only be queried via an API. `aPPR` additionally performs degree correction and regularization, allowing users to recover blocks from stochastic blockmodels. Leverages [`socialsampler`](https://github.com/alexpghayes/socialsampler) and [`twittercache`](https://github.com/alexpghayes/twittercache) to cache targeted network samples as the personalized pagerank calculations run. Read the [paper](https://arxiv.org/abs/1910.12937).

- [`vsp`](https://github.com/RoheLab/vsp) performs semi-parametric estimation of latent factors in random-dot product graphs by computing varimax rotations of the spectral embeddings of graphs. The resulting factors are sparse and interpretable. Read the [paper](https://arxiv.org/abs/2004.05387).

- [`fastRG`](https://rohelab.github.io/fastRG/) samples random-dot product graphs much faster than naive sampling procedures and is especially useful when running simulation studies. See [the paper](https://arxiv.org/abs/1703.02998) for a description of the `fastRG` core algorithm.

- [`fastadi`](https://github.com/RoheLab/fastadi) performs self-tuning matrix completion via adaptive thresholding, often outperforming `softImpute`. See [the paper](https://www.tandfonline.com/doi/full/10.1080/10618600.2018.1518238) for algorithmic and theoretical details. I have also extended this algorithm to work with matrices where the entire upper triangle is observed as part of some work on citation networks.

## #rstats

I am involved in a number of open source projects in the `tidyverse` and `tidymodels` orbits. In particular, I maintain the [`broom`](https://broom.tidymodels.org/) package, which currently has ~6 million downloads, and for my contributions am an author on the tidyverse paper. I intermittently participate in the Stan and ROpenSci communities as well.

## Please get in touch if...

- you'd like to hire me for a research or data science for social good internship,
- you want to discuss design of statistical modeling software,
- you want to collaborate on a research project, or
- you want to write an explainer together.

Outside of R, I'm a proficient Python user, and can pull together enough SQL, C++, Julia, and PySpark to get things done.

I am responsive on Twitter at [@alexpghayes](https://twitter.com/alexpghayes) and via email.

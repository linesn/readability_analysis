# readability_analysis
A demonstration of readability analysis performed using the Blog Authorship Corpus and Wikipedia.

This repository provides reproducible evidence to support an upcoming discussion on readability analysis that will be published in CHANCE magazine.

To reproduce the work contained herein should require fairly standard computing resources and Python tools. The most resource intensive notebook is `vocabulary_and_readability_blog_corpus.ipynb`: this was run on an Amazon EC2 m5d.4xlarge machine, with 16 virtual CPUs and 64 GiB of RAM. The environment was Amazon's Deep Learning AMI (Ubuntu 18.04.5 LTS) Version 26.0.  The `environment.yml` file in this directory provides details for the environment used, but this is overkill: the easiest way to run the notebooks provided is to just use `conda` or `pip` to install any modules not currently in your Python environment. The data used is not cached here, but is described in the notebooks, particularly `blog_data_prep.ipynb`, `wikipedia_readability.ipynb`, and `word_ease_analysis.ipynb`.

Please direct any questions or comments to nicholasalines@gmail.com.